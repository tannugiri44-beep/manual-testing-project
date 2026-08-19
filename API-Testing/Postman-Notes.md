# Postman API Testing Notes

## 📌 What is API Testing?

API Testing is the process of verifying that an API works correctly, returns the expected response, and handles different requests and inputs properly.

API testing mainly focuses on:

- Request validation
- Response validation
- Status code validation
- Response data validation
- Authentication
- Error handling
- Response time validation

---

## 🔹 HTTP Methods

| Method | Purpose |
|--------|---------|
| GET | Retrieve data from the server |
| POST | Create new data |
| PUT | Update existing data |
| PATCH | Partially update existing data |
| DELETE | Delete data |

---

## 🔹 Common HTTP Status Codes

| Status Code | Meaning |
|-------------|---------|
| 200 | OK – Request successful |
| 201 | Created – New resource created |
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

---

## 🔹 API Request Components

### 1. URL

The endpoint where the request is sent.

Example:

`https://dummyjson.com/products`

### 2. Method

Examples:

- GET
- POST
- PUT
- DELETE

### 3. Headers

Headers provide additional information about the request.

Example:

`Content-Type: application/json`

### 4. Query Parameters

Used to send additional parameters in the URL.

Example:

`/products/search?q=phone`

### 5. Request Body

Used mainly with POST, PUT, and PATCH requests.

Example:

```json
{
  "title": "Test Product",
  "price": 100
}

**🔹 Postman Test Scripts

Postman supports JavaScript-based test scripts using pm.test().

Status Code Validation
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
JSON Response Validation
pm.test("Response is JSON", function () {
    pm.response.to.be.json;
});
Response Data Validation
const data = pm.response.json();


pm.test("Product ID is 1", function () {
    pm.expect(data.id).to.eql(1);
});
🔹 Common API Testing Validations

During API testing, the following can be validated:

Status Code
Response Time
Response Format
JSON Structure
Required Fields
Data Types
IDs
Response Values
Authentication Token
Error Messages
🔐 Authentication Testing

Authentication APIs are used to verify user login and access control.

Example:

POST /user/login

Common validations include:

Status code
Response format
Access token
User information
Invalid login handling
🔹 CRUD Operations

CRUD stands for:

Operation	HTTP Method
Create	POST
Read	GET
Update	PUT / PATCH
Delete	DELETE

These operations were practiced using the DummyJSON API.

🔎 Search & Filter Testing

API search and filtering can be tested using query parameters.

Example:

GET /products/search?q=phone

Filtering can also be tested by passing appropriate query parameters.

🧪 Postman Collection Runner

Postman Collection Runner allows multiple API requests to be executed together.

It can be used to:

Run multiple requests
Execute test scripts
View passed/failed tests
Check overall test execution
Repeat API test runs
📊 API Testing Best Practices
Verify status codes
Validate response structure
Validate important response fields
Check response time
Test positive and negative scenarios
Test authentication
Use meaningful test names
Organize requests into collections
Use environment variables where required
Document test results
🛠️ Tool Used
Postman

Postman was used for:

Creating API requests
Sending requests
Writing test scripts
Validating responses
Running collections
Viewing test results
🎯 Project Practice

The concepts in these notes were applied in the DummyJSON API Testing project.

The project includes:

GET APIs
POST APIs
PUT APIs
DELETE APIs
Authentication
Search
Filtering
Response validation
Automated Postman assertions
👤 Author

Tannu Giri

QA Engineer | Manual Testing | API Testing | SQL | Postman | Jira | GitHub**
