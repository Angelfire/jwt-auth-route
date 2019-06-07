# Protecting routes using JWT

## Install dependencies
`npm i`

## Run the server
`npm start`

## Routes
### Login
Access to this router in order to create a new JWT

`http://localhost:5000/api/login`

### Posts (Protected route)
Add `Authorization` header with the previous JWT in order the `POST` a new post.

`http://localhost:5000/api/posts`