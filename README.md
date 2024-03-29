Building REST APIs with Spring Boot

***Goodreads Application
***Creating a Model Class
***Creating Service and Controller Classes
***Get Books API
***Get Book API
***Handling Exceptions
***Add Book API
***Update Book API
***Delete Book API

 Summary
---Getting Books
The Spring Boot annotation @GetMapping() is used to handle the HTTP GET requests to the specified path.
The @PathVariable annotation is used to bind the path parameter to the method parameter.

---Handling Exceptions
In Spring Boot we can use ResponseStatusException to raise an exception with a specified status code.
The status code HttpStatus.NOT_FOUND specifies that the requested resource was not found.

---Creating a Book (POST request)
The Spring Boot annotation @PostMapping() is used to handle the HTTP POST requests to the specified path.
The @RequestBody annotation is used to bind the request body to the method parameter.

---Updating a Book
The Spring Boot annotation @PutMapping() is used to handle the HTTP PUT requests to the specified path.

---Deleting a Book
The Spring Boot annotation @DeleteMapping() is used to handle the HTTP DELETE requests to the specified path.
