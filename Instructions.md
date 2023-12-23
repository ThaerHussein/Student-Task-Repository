## Instructions:
Follow these detailed step-by-step instructions to complete the task:

### Step 1: Implement Read (GET) Operation

1. **Create GET Endpoints:**
   - Open `CodedContoller.java`.
   - Add new methods annotated with `@GetMapping` to handle different read scenarios (e.g., get all items, get by ID, etc.).

2. **Implement Logic in Controller:**
   - Inside each GET method, implement logic to retrieve data.
   - Leverage `CodedService.java` for interacting with the data.

3. **Test GET Endpoints:**
   - Run the application.
   - Use tools like Postman or cURL to test each GET endpoint.
   - Verify that the expected data is retrieved for various scenarios.

### Step 2: Implement Update (PUT) Operation

1. **Create PUT Endpoint:**
   - In `CodedContoller.java`, add a new method annotated with `@PutMapping` to handle update requests.

2. **Implement Logic in Controller:**
   - Inside the PUT method, implement logic to update existing data.
   - Utilize `CodedService.java` to perform the update.

3. **Test Update Functionality:**
   - Run the application.
   - Use tools like Postman or cURL to test the update endpoint.
   - Verify that data is successfully modified for different scenarios.

### Step 3: Implement Delete (DELETE) Operation

1. **Create DELETE Endpoint:**
   - In `CodedContoller.java`, add a new method annotated with `@DeleteMapping` to handle delete requests.

2. **Implement Logic in Controller:**
   - Inside the DELETE method, implement logic to delete existing data.
   - Leverage `CodedService.java` to perform the deletion.

3. **Test Delete Functionality:**
   - Run the application.
   - Use tools like Postman or cURL to test the delete endpoint.
   - Verify that data is correctly removed for different scenarios.
