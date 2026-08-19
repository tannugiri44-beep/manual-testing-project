# QA Testing Portfolio – Manual & API Testing

## 👩‍💻 About This Repository

This repository contains hands-on QA and Software Testing projects demonstrating practical experience in Manual Testing, API Testing, Test Case Design, Defect Reporting, SQL, Postman, and Test Documentation.

---

# 📌 Project 1: E-Commerce Web Application – Manual Testing

## Project Overview

This project demonstrates manual testing of an e-commerce web application.

The project covers test planning, test scenario creation, test case design, test data preparation, test execution, defect reporting, and test summary reporting.

## Testing Activities

- Requirement Understanding
- Test Scenario Creation
- Test Case Creation
- Test Data Preparation
- Functional Testing
- Smoke Testing
- Sanity Testing
- Regression Testing
- Retesting
- Defect Reporting
- Test Execution
- Test Summary Reporting

## Tools Used

- Microsoft Excel
- Jira
- GitHub
- Chrome Browser

## Project Documents

- `01-Project-Overview.docx` – Project overview and testing details
- `02-Test-Scenarios.xlsx` – Test scenarios
- `03-Test-Cases.xlsx` – Detailed test cases
- `04-Flipkart-Test-Data.xlsx` – Test data
- `05-Flipkart-Test-Execution.xlsx` – Test execution results
- `06-Bug-Report.xlsx` – Defect/bug report
- `07-Test-Summary-Report.xlsx` – Test summary report

## Key Skills Demonstrated

- Manual Testing
- Test Case Design
- Test Scenario Design
- Functional Testing
- Regression Testing
- Smoke Testing
- Sanity Testing
- Retesting
- Defect Reporting
- Jira
- Microsoft Excel
- GitHub

---

# 📌 Project 2: DummyJSON API Testing – Postman

## Project Overview

A hands-on API testing project created using Postman and the public DummyJSON REST API.

The project demonstrates API testing fundamentals including CRUD operations, search, filtering, authentication, response validation, and automated test assertions.

## API Testing Coverage

- GET Requests
- POST Requests
- PUT Requests
- DELETE Requests
- Authentication / Login
- Search API
- Filter API
- Response Validation
- Status Code Validation
- JSON Response Validation
- Data Validation

## API Endpoints Tested

| Method | Endpoint | Test Coverage |
|--------|----------|---------------|
| POST | `/user/login` | Status, JSON response, access token |
| GET | `/products` | Status, JSON, products array |
| GET | `/products/{id}` | Status, JSON, product ID |
| GET | `/products/search?q=` | Search response validation |
| GET | `/products/categories` | Categories validation |
| GET | `/products/category/{category}` | Category filtering |
| POST | `/products/add` | Product creation |
| PUT | `/products/{id}` | Product update |
| DELETE | `/products/{id}` | Product deletion |
| GET | `/users` | Users array validation |
| GET | `/users/{id}` | User ID validation |
| GET | `/users/filter` | User filtering |
| POST | `/users/add` | User creation |
| DELETE | `/users/{id}` | User deletion |

## Tools & Technologies

- Postman
- DummyJSON REST API
- JavaScript
- Postman Test Scripts
- GitHub
- REST API
- JSON

## Test Automation

Postman `pm.test()` assertions were used to validate:

- HTTP Status Codes
- Response Time
- JSON Response
- Response Data
- Product/User IDs
- Authentication Token
- Created/Updated Data
- Delete Response

## Screenshots

API testing execution screenshots are available inside:

`API-Testing/`

---

# 🧪 Overall QA Skills

- Manual Testing
- API Testing
- Functional Testing
- Regression Testing
- Smoke Testing
- Sanity Testing
- Retesting
- Test Scenario Design
- Test Case Design
- Test Data Preparation
- Test Execution
- Defect Reporting
- SQL
- Postman
- Jira
- Microsoft Excel
- Git & GitHub
- JavaScript Basics

---

# 📂 Repository Structure

```text
manual-testing-project/
│
├── API-Testing/
│   ├── Postman Collection
│   └── API Testing Screenshots
│
├── Bug-Reports/
├── SQL-Practice/
├── Test-Cases/
│
├── 01-Project-Overview.docx
├── 02-Test-Scenarios.xlsx
├── 03-Test-Cases.xlsx
├── 04-Flipkart-Test-Data.xlsx
├── 05-Flipkart-Test-Execution.xlsx
├── 06-Bug-Report.xlsx
└── 07-Test-Summary-Report.xlsx
