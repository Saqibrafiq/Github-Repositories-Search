# Github Repositories Search

## dependancies

- node

- npm

## Installation

1. clone the project folder.

2. open the terminal and write `cd Github-Repo-Finder`.

3. install server dependancies by `npm install`.

4. install client dependancies by `cd client` then `npm install`.

## Run Client and server

1. To project directory by `cd ..`.

2. Write `npm run dev` to run both server and client.

## API Endpoints Table

Using the endpoints in the following table
| Http verb | Endpoint                                  | Description                                              |
|-----------|-------------------------------------------|----------------------------------------------------------|
| GET       | `/api/repos/search/?q=searchquery`        | endpoint to seach for repository.                        |
| GET       | `/api/bookmarks/list`                     | endpoint to return us a list of bookmarked repositories. |
| GET       | `/api/bookmarks/bookmark/:repository_id`  | add a repository by its id to bookmark list.             |
| GET       | `/api/bookmarks/remove/?id=repository_id` | to delete the bookmark of a repository by its id         |
| POST      | `/api/users/register`                     | register new user with name, username, password          |
| POST      | `/api/users/login`                        | user login with username, password                       |

## Project Details

Node Js server is created that listen on localhost:5000.
Request made to nodeJs server from React client with request url given above.
Response send from NodeJs server to React client and will be shown over the UI.
Github repo Api is called in node js server and then send to react client as described in the task description.
