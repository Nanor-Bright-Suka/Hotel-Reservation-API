# Property Management API

A RESTful backend API that enables users to securely manage their property listings. The application provides authentication, authorization, and CRUD operations for properties while following modern backend development practices such as layered architecture, validation, exception handling, and testing.

## Features

* User authentication and authorization
* Secure JWT-based authentication
* Rate limiting with redis
* User registration and login
* Property management
* Input validation
* Global exception handling
* Unit testing
* Integration testing

## Tech Stack

* Java 21
* Spring Boot
* Spring Security
* Spring Data JPA
* PostgreSQL
* Maven
* JUnit 5
* Mockito
* MockMvc
* Testcontainers
* Docker

## Project Structure

The project follows a layered architecture:

* Controller Layer
* Service Layer
* Repository Layer
* Entity Layer
* DTO Layer
* Configuration Layer
* Security Layer
* Exception Handling
* Validation

## Testing

The project includes comprehensive  testing.

### Unit Tests

Unit tests verify the business logic of individual components using JUnit 5 and Mockito. Dependencies are mocked to ensure each class is tested in isolation.

### Integration Tests

Integration tests verify that the application behaves correctly as a whole by testing API endpoints, persistence, validation, and security.

## Security

* JWT Authentication
* Password encryption with BCrypt
* Role-based authorization
* Stateless authentication
* Protected API endpoints

## Validation

Incoming requests are validated before processing to ensure data integrity and provide meaningful error responses.

## Error Handling

The API uses centralized exception handling to return consistent and descriptive error responses.

## Running the Application

### Prerequisites

* Java 21
* Maven
* PostgreSQL


```bash
mvn spring-boot:run
```

## Future Improvements

* Property image uploads
* Property search and advanced filtering
* Property favorites
* Notifications

## License

This project is available for educational and portfolio purposes.
