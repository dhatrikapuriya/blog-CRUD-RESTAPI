# blog-CRUD-RESTAPI
A REST API developed using Django Rest Framework for CRUD operations on a blog application.

## Resource points

1. GET list of users
   ```
   http://127.0.0.1:8000/users/
   ```
2. GET information of users by user id.
   ```
   http://127.0.0.1:8000/users/<id>
   ```
3. GET all posts
   ```
   http://127.0.0.1:8000/posts/
   ```
4. GET, Delete, Update own post
   ```
   http://127.0.0.1:8000/posts/<id>
   ```
5. GET Comments on posts
   ```
   http://127.0.0.1:8000/comments/
   ```
6. PUT, DELETE and GET comments on posts by comment id
   ```
   http://127.0.0.1:8000/comments/<id>
   ```
   User can delete or update their own comments only.
 
 
User can log in using the button on the right most top corner.
For creating new user, visit ``` http://127.0.0.1:8000/admin ```. 
Login credentials are 
```
username : admin
password : admin12345
```
## Postman Collection
[Postman Collection link](https://www.getpostman.com/collections/9c8ded04ec9fb8629162)

