# JSONPlaceholder API Testing using Postman

## About the Project

This project demonstrates API testing using **Postman** with the JSONPlaceholder REST API.

The project focuses on testing CRUD operations, validating API responses, creating positive and negative test scenarios, and writing automated test scripts in Postman.

## API Tested

**JSONPlaceholder**  
A free fake REST API used for testing and development.

Base URL:

```text
https://jsonplaceholder.typicode.com
Tools & Technologies
Postman
JavaScript
JSON
REST API
GitHub
Microsoft Excel
API Operations Tested
Method	Operation	Endpoint
GET	Retrieve posts	/posts
GET	Retrieve a specific post	/posts/{id}
POST	Create a new post	/posts
PUT	Update an existing post	/posts/{id}
DELETE	Delete a post	/posts/{id}
Testing Performed
Functional Testing
Verified HTTP status codes
Validated response bodies
Checked response structure
Verified request and response data
Tested CRUD operations
Positive Testing

Tested valid requests and verified that the API returned the expected responses.

Examples:

Valid GET request
Valid POST request
Valid PUT request
Valid DELETE request
Valid resource IDs
Negative Testing

Tested invalid or unexpected inputs to verify API behavior.

Examples:

Invalid resource IDs
Non-existing resources
Invalid request data
Unexpected input values
Automated Tests

Postman test scripts were created using JavaScript to automate response validation.

The automated tests include checks for:

Status codes
Response time
Response body
Required fields
Data validation
Successful API responses

Example:

pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});

pm.test("Response is JSON", function () {
    pm.response.to.be.json;
});
Test Cases

Detailed test cases are maintained in an Excel file.

The test cases include:

Test Case ID
Test Scenario
Request Method
Endpoint
Test Data
Expected Result
Actual Result
Status

📄 View Test Cases

Postman Collection

The complete Postman collection containing the API requests and automated test scripts is available in the repository.

📁 View Postman Collection

Screenshots
Postman Collection

Automated API Tests

Collection Run Results

Project Structure
JSONPlaceholder-API-Testing/
│
├── README.md
│
├── Postman/
│   └── Postman Collection
│
├── Screenshots/
│   ├── automated-api-tests.png
│   ├── collection-run-results.png
│   └── postman-collection.png
│
└── Test-Cases/
    └── API Test Cases Excel File
What I Learned

Through this project, I gained practical experience in:

Understanding REST APIs
Working with HTTP methods
Testing CRUD operations
Creating API test cases
Performing positive and negative testing
Validating API responses
Writing automated tests using JavaScript in Postman
Using variables in Postman
Running collections using Postman Collection Runner
Documenting test cases and results
Using GitHub to manage and showcase a testing project
Conclusion

This project helped me build practical knowledge of API testing and software testing fundamentals using Postman. It demonstrates my ability to create test cases, execute API requests, validate responses, automate basic API checks, and document testing activities.
