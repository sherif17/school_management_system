# [School Management System API](https://schoolmanagmentsystem.onrender.com/api-docs/#/)

## Overview
The School Management System API is a comprehensive backend solution designed to facilitate the management of users, schools, classrooms, and students within an educational environment. It offers features for user authentication, authorization, and CRUD operations on essential entities such as users, schools, and classrooms.

## Key Features

### 1. User Management
- Create an initial super admin with elevated privileges.
- Authenticate users and generate access tokens using JWT.
- Manage user roles, including super admins, school admins, and regular users.

### 2. School Management
- Create, update, and delete schools with super admin privileges.
- Assign school admins to specific schools.
- Ensure that only super admins can perform school-related operations.

### 3. Classroom Management
- Allow school admins to create, list, and delete classrooms within their respective schools.
- Implement proper error handling for classroom operations.

### 4. Security Measures
- Use JWT tokens for user authentication and authorization.
- Implement bcrypt for password hashing.
- Ensure that sensitive operations require super admin privileges.

### 5. Swagger Documentation
- Provide comprehensive Swagger documentation for each API endpoint.
- Include details on request/response formats, required parameters, and possible error scenarios.

## Technologies Used
- Node.js for server-side scripting.
- Express.js for building the API.
- MongoDB as the database for storing user, school, and classroom information.
- JWT for secure user authentication.
- Bcrypt for password hashing.
- Swagger for API documentation.

## Deployment [link](https://schoolmanagmentsystem.onrender.com/api-docs/#/)
Deploy the School Management System API on a cloud service like Render, ensuring seamless access and scalability.

