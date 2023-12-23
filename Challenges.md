## Challenges:
### Challenge 1: Implement Read (GET) Operation
1. Extend the existing `CodedContoller.java` to include additional GET endpoints.
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
   - Open `CodedContoller.java`.
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
   - In `CodedContoller.java`, add a new method annotated with `@PutMapping` to handle update requests.

2. **Implement Logic in Controller:**
   - Inside the PUT method, implement logic to update existing data.
   - Utilize `DemoService.java` to perform the update.

3. **Test Update Functionality:**
   - Run the application.
   - Use tools like Postman or cURL to test the update endpoint.
   - Verify that data is successfully modified for different scenarios.

### Step 3: Implement Delete (DELETE) Operation

1. **Create DELETE Endpoint:**
   - In `CodedContoller.java`, add a new method annotated with `@DeleteMapping` to handle delete requests.

2. **Implement Logic in Controller:**
   - Inside the DELETE method, implement logic to delete existing data.
   - Leverage `DemoService.java` to perform the deletion.

3. **Test Delete Functionality:**
   - Run the application.
   - Use tools like Postman or cURL to test the delete endpoint.
   - Verify that data is correctly removed for different scenarios.
