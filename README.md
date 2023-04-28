# json-server
json-server for  Airways-rs-school 

## Install:
`npm install -g json-server`

### Routes:
- START SERVER WORK - `json-server db.json -m ./node_modules/json-server-auth`

- home - `http://localhost:4000/`

- get users from db - `http://localhost:4000/users`

- get cities from db - `http://localhost:4000/cities`

- get tickets from db - `http://localhost:4000/tickets`

- get ticket by id from db - `http://localhost:4000/tickets/id`

- get tickets and filter them - `http://localhost:4000/tickets?filterName=filterCriteria`

- register - `POST /register` (*email* and *password* are required in the *request* body. **Must be valid and in a single copy** )

- login - `POST /login` (*email* and *password* are required in the *request* body.)
