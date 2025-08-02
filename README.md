#Postman Tests for JSONPlaceholder API

This pet project demonstrates API testing skills using Postman.
It targets the public API: https://jsonplaceholder.typicode.com

The collection includes GET, POST, PATCH, and DELETE requests with extended automated tests verifying response correctness.

##Collection Structure
The collection covers the following endpoints:

|Method|	Endpoint	Description
|GET|	/posts	Retrieve a list of posts
|GET	/posts/1	Retrieve a specific post
|POST	/posts	Create a new post
|PATCH	/posts/1	Partially update a post
|DELETE	/posts/1	Delete a post
|DELETE	/posts/2	Delete another post
|GET	/comments	Retrieve list of comments
|GET	/users	Retrieve list of users

##What is Tested
Status code validation (e.g., 200, 201, 204)

Data structure and types (e.g., /posts returns an array of objects with expected fields)

Content of specific fields (title, body, userId)

Empty response after deletion ({})

##How to Use
Open Postman.

Import the file:
Postman_Collection_Advanced_Tests.json

Run individual requests or use the Runner to execute the entire collection.

##About JSONPlaceholder API
JSONPlaceholder is a fake REST API used for testing and prototyping.
It allows working with the following resources:

posts — user posts (e.g., blog entries)

comments — comments for posts

users — system users

##Note: The API doesn’t persist changes. POST, PATCH, and DELETE work, but they don’t affect actual data.
