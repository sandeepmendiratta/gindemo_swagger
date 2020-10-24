
### Generate API Documentation
```
make doc
```
### Run the service
```
make run
```

### Open swagger UI
http://localhost:8080/swagger/index.html


### Steps

- add the content to main.go
// @title This is My User API
// @description User microservice server for test.
// @schemes http https
// @securityDefinitions.basic BasicAuth

- add the content in the handler file
// ListUser is the handler of list user endpoint
// @Summary List users
// @Description list all the users based on filter given
// @Tags user
// @Produce  json
// @Success 200 {object} model.UserList
// @Router /users/ [get]
