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
(Json github)[]
(npm json link)[https://www.npmjs.com/package/json-server/v/0.17.4]
installing local command `npm i json-server@0.17.4`
installing global command `npm i -g json-server@0.17.4`

create file db.json

paste this data into the db.json file
```
{
    "posts": [
        {
            "id": 1,
            "title": "First Post",
            "content": "This is the content of the first post.",
            "author": "John Doe",
            "date": "2023-10-01"
        },
        {
            "id": 2,
            "title": "Second Post",
            "content": "This is the content of the second post.",
            "author": "Jane Smith",
            "date": "2023-10-02"
        }
    ]
}
```


