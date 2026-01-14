# web-service-gin
This example is based on the Go [tutorial](https://go.dev/doc/tutorial/web-service-gin).  

A very simple backend server written in Golang using the Gin framework. It implements:
1. a GET method for all of the data in the temporary JSON
2. a GET method by user's specified ID in the temporary JSON
3. a POST method that creates a new record and adds it to the RAM
4. a DELETE method that deletes a record from RAM specifed by ID 