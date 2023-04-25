# json-server
json-server for  Airways-rs-school 

## Install:
`npm install -g json-server`

### Routes:
- START SERVER WORK - `json-server db.json -m ./node_modules/json-server-auth`

- home - `http://localhost:4000/`

- get users from db - `http://localhost:4000/users`

- get tickets from db - `http://localhost:4000/tickets`

- register - `POST /register` (*email* and *password* are required in the *request* body. **Must be valid and in a single copy** )

- login - `POST /login` (*email* and *password* are required in the *request* body.)
