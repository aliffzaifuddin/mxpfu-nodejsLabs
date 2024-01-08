# Node.js

# This practise helps to learn token-based authentication when retrieve and update data from the server using GET, POST, PUT and DELETE method. 

You have an Express server that has been configured to run at port 5000. When you access the server with /user you can access the endpoints defined in routes/users.js.
Recall that GET, POST, PUT and DELETE are the commonly used HTTP methods to perform CRUD operations. Those operations retrieve and send data to the server.

# GET is used to request data from a specified resource.
# POST is used to send data to a server for creating a resource.
# PUT is used to send data to a server to update a resource.
# DELETE is used for deleting a specified resource.

This lab requires some packages to be installed. The express and nodemon package for starting and running the Express server and jsonwebtoken and express-session for session based authentication.
1.express - This is for creating a server to serve the API endpoints.
2.nodemon - This will help to restart the server when you make any changes to the code.
3.jsonwebtoken - This package helps in generating a JSON web token which we will use for authentication. A JSON web token (JWT) is a JSON object used to communicate information securely over the internet (between two parties). It can be used for information exchange and is typically used for authentication systems.
4.express-session - This package will help us to maintain the authentication for the session.

# Objectives:
Create API endpoints to perform Create, Retrieve, Update and Delete operations on transient data with an Express server.
Implement authentication at the session level using JSON Web Tokens (JWT) for authorized access.
