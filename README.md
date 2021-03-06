# jjk-sample-test-db

It is just mock JSON data for testing an API service for Auth and CRUD operations.

Use json-server on the db.json server to use the mock API.

## How to use?

1. Install json-server globally on your system.

```sh
npm install -g json-server
```

2. Clone this repository on your system.

```sh
git clone https://github.com/praj31/jjk-sample-test-db.git
```

3. From the root directory of the cloned project, execute the following command.

```sh
json-server -p 5000 --watch
```

The `-p` flag is used to specify the port number to run the mock API on. 
The `--watch` flag watches the file for changes and reflects it inside the file accordingly.

4. Open your browser and visit http://localhost:5000/users to see all the users data. Please replace the port number with the one you specified if done so.
5. Open your browser and visit http://localhost:5000/posts to see all the posts data.


## API Endpoints
|METHOD  |ENDPOINT    |DESCRIPTION                   |
|:-------|:-----------|:-----------------------------|
|GET     |/users      |get all users                 |
|GET     |/posts      |get all posts                 |
|GET     |/users/:id  |get a particular user by ID   |  
|GET     |/posts/:id  |get a particular post by ID   |    
|POST    |/users      |add a new user                |
|POST    |/posts      |add a new post                |
|PUT     |/users/:id  |update a particular user by ID|  
|PUT     |/posts/:id  |update a particular post by ID|  
|DELETE  |/users/:id  |delete a particular user by ID|  
|DELETE  |/posts/:id  |delete a particular post by ID|   
