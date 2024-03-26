# Reqres
Project Name: REQRES
Base URL: https://reqres.in/api
Collection:[Swagger]
            Request 1:POST create user  /register
                      Row data : Required,
            Request 2:POST create session  /login
                      Row data : Required,
            Request 3:GET Fetches user list /users?page=1&per_page=3,
            Request 4:GET Fetch user by id /users/1,
            Request 5:GET get resource list /{resource}?page=1&per_page=3, 
            Request 6:PUT updates a user /users/1,
            Request 7:PATCH updates a user /users/1,
            Request 8:DELETE Delete a user /users/1,
            Request 9:GET fetches an unknown resource /users/1,
            Request 10:PUT update unknown resource /{resource}/3,
            Request 11:PATCH update unknown resource /{resource}/3,
            Request 12:DELETE delete unknown resource /{resource}/3,
            Request 13:DELETE logout session /logout.

Collection:[user data]
           Request 1:GET List of users  api/users?page=2,
           Request 2:GET single user  api/users/2,
           Request 3:GET single user not found api/users/23,
           Request 4:GET list resource  api/unknown,
           Request 5:GET single resource  api/unknown/2,
           Request 6:GET single resource not found  api/unknown/23,
           Request 7:POST create api/users
                     Row data : Required,
           Request 8:PUT update api/users/2,
           Request 9:DELETE delete user  api/users/2,
           Request 10:POST register successful api/register
                      Row data : Required,
           Request 11:POST register unsuccessful api/register
                      Row data : Required,
           Request 12:POST login successful api/login
                      Row data : Required,
           Request 13:POST login unsuccessful api/login
                      Row data : Required,
           Request 14:GET delayed response  /api/users?delay=3

            
            
            
            
