**Title:** E-Commerce Product Management

**Description:** You are tasked with building a basic e-commerce product management system using Node.js, MongoDB, and NestJS. This system should allow users to add, view, update, and delete products.

**Requirements:**

1.  Create a product model with at least the following fields:

    - Product name
    - Description
    - Price
    - Category (e.g., Electronics, Clothing, Books)
    - Inventory quantity

2.  Implement the following API endpoints using NestJS:

    - Create a new product
    - View a list of products
    - View a single product by ID
    - Update a product's details
    - Delete a product

3.  Implement JWT authentication for user registration and login. Return a JWT token upon successful login.
4.  Implement validation and error handling for the API endpoints. Ensure that the API returns appropriate error messages for validation failures and other errors.
5.  Use MongoDB as the database to store product data. You can use an ODM library like Mongoose to work with MongoDB.
6.  Secure the application against common security vulnerabilities.
7.  Write unit tests for your controllers and services to ensure the functionality of your endpoints.
8.  Use proper project structure and organization following NestJS best practices.

**Bonus (Optional):**

- Implement user roles (admin, regular user) and restrict certain actions to admin users.
- Implement image upload and storage for product images.
- Implement search and filter functionality for products.
- Implement pagination and sorting for product lists.
- Containerize the application using Docker.
- Deploy the application to a cloud platform of your choice.

**Submission:** Provide a GitHub repository with your NestJS project and a README file with instructions on how to run and test the application. Make sure to include any necessary environment variables or configuration settings.

**Evaluation Criteria:**

1.  Code quality and organization.
2.  Completeness of the implemented features.
3.  Proper error handling and validation.
4.  Security practices.
5.  Use of best practices in NestJS and MongoDB.
6.  Unit test coverage and quality.
