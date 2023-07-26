# Implementing JWT Authentication in Golang

In this article, we will learn about implementing JWT Authentication in Golang REST APIs and securing it with Authentication Middleware. We will be building a simple, yet neatly organized Golang REST API with packages like Gin for Routing (mostly), GORM for persisting user data to a MySQL Database, and so on.


- Setting up Mysql Database with GORM
Create manually DataBase and connect to mysql server using Workbench
CREATE DATABASE jwt_demo;

- User Registration & Password Hashing
register an new user and also check in mysql workbench 
we have send request 
SELECT * FROM jwt_demo.users;
- Generating JWTs
We have to just passing the user credentials to the api/token endpoint. This is what a client will be doing to generate authentication tokens.
Send the request. You can see that the API responds with an actual JWT token.
we have send request 
- Authentication Middleware to Valid JWTs
- Gin Routing & Grouping
- Testing Golang API with VSCode REST Client