# Task Manager API

Welcome to the Task Manager API project! This project aims to provide a simple and efficient way for users to manage their tasks. As a backend developer, you'll find this project helpful for learning Java backend development, including RESTful APIs, database integration, authentication, and more.

## Features

- User Registration and Authentication: Users can register and log in to access their tasks securely.
- Task CRUD Operations: Users can create, read, update, and delete tasks.
- Task Filtering and Sorting: Users can filter and sort tasks based on different parameters.
- User-specific Tasks: Each user can only access and manage their own tasks.
- Database Integration: The API integrates with a PostgreSQL database.
- Validation and Error Handling: Proper validation and error handling ensure a reliable API.
- API Documentation: Comprehensive API documentation for easy integration.

## Tech Stack

- Java (Spring Boot): The backend is built using the Spring Boot framework.
- Database: User information and tasks are stored in a PostgreSQL database.
- Authentication: JWT-based authentication is used to secure user accounts.
- API Documentation: API documentation is generated using Swagger.

## Getting Started

1. **Clone the Repository:** `git clone https://github.com/your-username/task-manager-api.git`
2. **Navigate to the Project Directory:** `cd task-manager-api`
3. **Install Dependencies:** `mvn install` (Ensure you have Maven installed)
4. **Configure the Database:** Set up your PostgreSQL connection in `application.properties` file.
5. **Run the Application:** `mvn spring-boot:run`
6. **Access the API Documentation:** Open your browser and go to `http://localhost:8080/swagger-ui.html`

## API Endpoints

- **POST /api/register:** Register a new user account.
- **POST /api/login:** Log in and receive an authentication token.
- **GET /api/tasks:** Get a list of tasks.
- **GET /api/tasks/{taskId}:** Get details of a specific task.
- **POST /api/tasks:** Create a new task.
- **PUT /api/tasks/{taskId}:** Update the details of a task.
- **DELETE /api/tasks/{taskId}:** Delete a task.

## Authentication

- JWT (JSON Web Token) is used for authentication.
- Include the JWT token in the `Authorization` header for protected routes.

## Contribute

Contributions are welcome! Feel free to submit issues and pull requests for improvements.

## License

This project is licensed under the MIT License.
