# NPM
## initializing
to initialize:
``` 
npm init
```
## installing the modules
Creates modules and everything else that is required (dependency tree)
```
npm i prompt-sync
```

## package-lock.json & package.json
`package-lock.json` :Locks down the exact versions of every package and sub-package installed. 
`package.json` :Describes your project and its dependencies.

## Local vs global installation
To install globally
`npm install -g nodemon`

# installing JSON server

JSONPlaceholder for fetching dummy data.
JSON Server gives you a simple rest server when you don't have a backend built.
<!-- (Json github)[] -->
(npm json link)[https://www.npmjs.com/package/json-server/v/0.17.4#getting-started]
installing local command `npm i json-server@0.17.4`
installing global command `npm i -g json-server@0.17.4`

Create a `db.json` file with some data

```
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" },
    { "id": 2, "title": "json-server2", "author": "typicode2" },
    { "id": 3, "title": "json-server3", "author": "typicode3" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```
Start JSON Server

`json-server --watch db.json`

In your `index.js` add the following to access data in your db.json

```
fetch('http://localhost:3000/posts')
      .then(response => response.json())
      .then(json => console.log(json))
```
to specify port `db.json --port 4000`

`ctrl+z` pushes the process to the back ground.

You don't need the --watch tag

# PostMan

Create a postman account [here:](https://web.postman.co/home).

Create a workspace
On the left side menu (explore our templates) choose API testing then click next

create a team by following the popups

in the postman window next to getting started tab create a new tab

and paste this `https://jsonplaceholder.typicode.com/todos/1`

use this image for reference:

![Screenshot](/assets/img/postman.png)


Congrats!!You've tested your API.

Ways to access postman:
-App
-VS code extension
-web

# Lucide icons

icons on [Lucide](https://lucide.dev/icons/)


