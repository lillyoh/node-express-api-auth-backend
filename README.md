# REST Express API starter with user authentication

Get a project off the ground fast with this backend boilerplate. This repo contains an Express server built in Node.js with register and login routes, password hashing, and authentication.

### Getting started
```
git clone https://github.com/lillyoh/node-express-api-auth-backend.git my-app
cd my-app
npm install
```

### Configuring the database
* Create your own MongoDB Atlas cluster and obtain the connection string from MongoDB. 
* Create a ```.env``` file in the root directory with the connection string assigned to the ```DB_CONNECT``` environment variable. 

### Features

* Express server in Node.js
* Route handlers for register and login
* Connected to MongoDB 
* User model 
* Data validation 
* Password hashing with bcrypt 
* Authentication with JSON Web Tokens
* Protected route with token authentication middleware
* Automatic server reloading with nodemon
* See a full tutorial on how to build this project from scratch at [lillyoh.com/backend-api-tutorial](https://lillyoh.com/backend-api-tutorial)
