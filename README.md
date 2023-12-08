# Student Task Repository

This repository contains a task for students along with challenges and instructions.


## Instructions for Students:

1. Clone this repository to your local machine.
2. Read the task description carefully.
3. Complete the challenges outlined in [Challenges.md](Challenges.md).
4. Follow the step-by-step instructions in [Instructions.md](Instructions.md).
5. Submit your solution by [specify the submission method].

## Challenges:
### Challenge 1: Implement Read (GET) Operation
1. Extend the existing `DemoController.java` to include additional GET endpoints.
2. Implement logic to retrieve data based on various criteria (e.g., all items, specific IDs, etc.).
3. Test the new GET endpoints using different scenarios and verify the retrieved data.

### Challenge 2: Implement Update (PUT) Operation
1. Add an endpoint to handle PUT requests for updating existing data.
2. Implement the logic to modify existing data using the PUT method.
3. Test the update functionality with different scenarios.

### Challenge 3: Implement Delete (DELETE) Operation
1. Create a DELETE endpoint to handle requests for removing data.
2. Implement the logic to delete existing data using the DELETE method.
3. Test the delete functionality and ensure proper error handling.

## Instructions:
Follow these detailed step-by-step instructions to complete the task:

### Step 1: Implement Read (GET) Operation

1. **Create GET Endpoints:**
   - Open `DemoController.java`.
   - Add new methods annotated with `@GetMapping` to handle different read scenarios (e.g., get all items, get by ID, etc.).

2. **Implement Logic in Controller:**
   - Inside each GET method, implement logic to retrieve data.
   - Leverage `DemoService.java` for interacting with the data.

3. **Test GET Endpoints:**
   - Run the application.
   - Use tools like Postman or cURL to test each GET endpoint.
   - Verify that the expected data is retrieved for various scenarios.

### Step 2: Implement Update (PUT) Operation

1. **Create PUT Endpoint:**
   - In `DemoController.java`, add a new method annotated with `@PutMapping` to handle update requests.

2. **Implement Logic in Controller:**
   - Inside the PUT method, implement logic to update existing data.
   - Utilize `DemoService.java` to perform the update.

3. **Test Update Functionality:**
   - Run the application.
   - Use tools like Postman or cURL to test the update endpoint.
   - Verify that data is successfully modified for different scenarios.

### Step 3: Implement Delete (DELETE) Operation

1. **Create DELETE Endpoint:**
   - In `DemoController.java`, add a new method annotated with `@DeleteMapping` to handle delete requests.

2. **Implement Logic in Controller:**
   - Inside the DELETE method, implement logic to delete existing data.
   - Leverage `DemoService.java` to perform the deletion.

3. **Test Delete Functionality:**
   - Run the application.
   - Use tools like Postman or cURL to test the delete endpoint.
   - Verify that data is correctly removed for different scenarios.

### General Instructions:

- Ensure appropriate error handling for edge cases (e.g., attempting to update or delete non-existent data).
- Document your code using comments to explain key sections and any challenges faced.
- Follow RESTful best practices, including proper HTTP status codes and response formats.
## Resources:
### 1. [Spring Framework Documentation](https://spring.io/guides)
Explore the official Spring Framework documentation for in-depth information on Spring Boot and its various features.

### 2. [Spring Boot Documentation](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
Refer to the official Spring Boot documentation for detailed explanations of Spring Boot features, annotations, and best practices.

### 3. [Baeldung Spring Boot Tutorials](https://www.baeldung.com/)
Baeldung offers a variety of tutorials covering Spring Boot, REST APIs, and CRUD operations. Search for specific topics related to your task.

### 4. [RESTful API Design Best Practices](https://restfulapi.net/)
Understand best practices for designing RESTful APIs, including resource naming, HTTP methods, and response formats.

### 5. [Spring Boot CRUD Operations Example](https://www.javaguides.net/2018/09/spring-boot-2-jpa-hibernate-5-crud-restful-api-tutorial.html)
Follow a comprehensive tutorial on building a Spring Boot application with CRUD operations using JPA and Hibernate.

### 6. [Postman Documentation](https://learning.postman.com/docs/getting-started/introduction/)
Learn how to use Postman for testing and exploring your RESTful APIs.

### 7. [Building RESTful Web Services with Spring Boot](https://www.baeldung.com/spring-boot-restful-web-services)
A tutorial on creating RESTful web services with Spring Boot, covering key concepts.

### 8. [Spring Data JPA Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
Explore the documentation for Spring Data JPA to understand how to work with data repositories.

### 9. [Stack Overflow](https://stackoverflow.com/)
Search for and ask questions related to specific challenges or issues you may encounter during the task.

### 10. [Java Programming Community](#)
Engage with the broader Java programming community on forums, social media, and discussion groups to seek advice and share experiences.

