# Apache-HttpClient
Make an HTTP GET, POST, PUT, and DELETE requests using Apache HttpClient 4.5.13

### Setup

* Let's discuss how to use `HttpClient` in real-time projects. Consider Spring boot Restful CRUD APIs in here `https://github.com/MadushanSandaru1/restapi-test`

## API Details


### Get all users - GET
```
http://localhost:8080/api/v1/user/all
```

### Get user by id - GET 
```
http://localhost:8080/api/v1/user/1
```

### Create user - POST
```
http://localhost:8080/api/v1/user/create
```

```json
{
    "name": "Madushan",
    "email": "madushan@gmail.com",
    "dob": "1998-01-17"
}
```

### Update user - PUT
```
http://localhost:8080/api/v1/user/update/1
````

```json
{
    "name": "Madushan",
    "email": "madushan@gmail.com",
    "dob": "1998-01-17"
}
```

### Delete user - DELETE
```
http://localhost:8080/api/v1/user/delete/1
```
