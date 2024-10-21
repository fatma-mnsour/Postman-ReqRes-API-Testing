# Postman-ReqRes-API-Testing

Introduction
This repository contains a Postman collection for testing various endpoints of the ReqRes API, a mock API used for simulating HTTP requests. The collection includes a range of tests for basic user operations like listing users, retrieving a single user, creating, updating, and deleting users, and handling resource-specific requests.

#Features
List Users: Retrieve a list of users with pagination.
Single User: Get details for a single user by ID.
Single User Not Found: Test the response for a non-existent user.
Create User: Create a new user with POST.
Update User: Update user information using PUT or PATCH.
Delete User: Delete a user by ID.
Successful Registration: Simulate a successful user registration.
Unsuccessful Registration: Test the response when registration details are incomplete.
Delayed Response: Simulate and test a delayed API response.

Environment Variables

{{Base_URL}}: Base URL for the ReqRes API (e.g., https://reqres.in/).

{{User_ID}}: Collection variable used for dynamic user ID in requests.
Setup Instructions
Import the Collection:
Open Postman and click on Import.
Upload the ReqRes.postman_collection.json file.
Set Up Environment:
Create a new environment in Postman with the variable Base_URL set to https://reqres.in/.
Run the Collection:
Select the environment and run individual requests or the entire collection.
