**Title:** Online Quiz Platform

**Description:** You are tasked with building an online quiz platform using Node.js, MongoDB, and Express.js. This platform should allow users to create and participate in quizzes. Users can answer questions, see their scores, and view their quiz history.

**Requirements:**

1.  Create a user model with the following fields:

    - Username
    - Email
    - Password (hashed)

2.  Create a quiz model with the following fields:

    - Title
    - Description
    - Questions (an array of objects with a question and multiple choices)
    - Time limit for the quiz

3.  Implement the following API endpoints using Express.js:

    - User registration
    - User login
    - Create a new quiz
    - View a list of available quizzes
    - Start and complete a quiz
    - View user quiz history (completed quizzes)

4.  Implement JWT authentication for user registration and login. Return a JWT token upon successful login.
1.  Implement validation and error handling for the API endpoints. Ensure that the API returns appropriate error messages for validation failures and other errors.
1.  Use MongoDB as the database to store user and quiz data. You can use an ODM library like Mongoose to work with MongoDB.
1.  Secure the application against common security vulnerabilities.
1.  Write unit tests for your controllers and services to ensure the functionality of your endpoints.
1. Use proper project structure and organization following Express.js and Node.js best practices.

**Bonus (Optional):**

- Implement user roles (admin, regular user) and restrict certain actions to admin users.
- Allow users to review their quiz answers and scores after completion.
- Implement real-time quiz updates using WebSockets.
- Containerize the application using Docker.
- Deploy the application to a cloud platform of your choice.
- Use Redis to store quiz state (e.g., which questions were answered, time remaining) during the quiz. This can help users continue the quiz where they left off.

**Submission:** Provide a GitHub repository with your Express.js project and a README file with instructions on how to run and test the application. Make sure to include any necessary environment variables or configuration settings.

**Evaluation Criteria:**

1.  Code quality and organization.
2.  Completeness of the implemented features.
3.  Proper error handling and validation.
4.  Security practices.
5.  Use of best practices in Express.js, MongoDB, and Redis.
6.  Unit test coverage and quality.
