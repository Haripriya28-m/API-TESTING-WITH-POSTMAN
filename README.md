📘 API Testing with Postman
This project demonstrates API testing using Postman and GitHub Actions. It covers basic CRUD operations tested against a sample REST API (jsonplaceholder.typicode.com).

📁 Project Structure

API-TESTING-WITH-POSTMAN/
│
├── postman_collection.json               # Postman collection with test cases
├── baseURL.postman_environment.json      # Postman environment file with base URL
└── .github/
    └── workflows/
        └── workflow-file.yaml            # GitHub Actions workflow for test automation
✅ Test Scenarios Covered
GET /posts – Retrieve all posts

GET /posts/{id} – Retrieve a single post

POST /posts – Create a new post

PUT /posts/{id} – Update an existing post

DELETE /posts/{id} – Delete a post

🧪 How to Run Tests Locally (Optional)
Install Postman

Import the collection and environment

Click Run Collection to execute the tests

🔄 Automation with GitHub Actions
The test suite is automated using GitHub Actions:

Runs Newman via Node.js

Executes all test cases in the collection

Validates environment setup using baseURL

📦 Workflow Summary
The GitHub Actions workflow performs the following steps:

Sets up Node.js environment

Installs Newman

Runs tests using the Postman collection and environment file

You can view the automated test run results under the Actions tab of this repository.

📌 API Base URL
We use the public mock API:

https://jsonplaceholder.typicode.com
