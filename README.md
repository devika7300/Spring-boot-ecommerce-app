# E-commerce Backend Application

## Introduction
This is a backend application for an e-commerce platform built with Java Spring Boot. It is designed to handle all backend functionalities such as user authentication, product management, order processing, and more using REST APIs.

## Features
- **User Authentication and Authorization**: Implemented using Spring Security 6 and JWT for secure access to the API endpoints.
- **Product Management**: APIs to create, update, delete, and retrieve products.
- **Order Processing**: APIs to manage customer orders from creation to completion.
- **Secure Payments**: Integration with payment gateways for processing payments.

## Technologies Used
- **Spring Boot**: For creating the application framework and server.
- **PostgreSQL**: As the relational database for storing all application data.
- **Spring Security 6**: For securing the application using JWT-based authentication.
- **JWT (JSON Web Tokens)**: For handling the security tokens used in authentication and authorization.
- **Postman**: Recommended tool for testing and interacting with the REST API endpoints.

## Getting Started

### Prerequisites
- Java JDK 11 or newer
- Maven
- PostgreSQL installed and running on your local machine or a remote server.
- Postman for API testing.

### Installation
1. Clone the repository:
   git clone https://github.com/yourusername/spring-boot-ecommerce-app.git
2. Navigate to the project directory:
   cd ecomm-backend
3. Configure PostgreSQL:
   Ensure PostgreSQL is running.
   Create a database for the application.
   Update the application.properties file with your database credentials and URL.
   Build the project:
   mvn clean install
4. Run the application:
   mvn spring-boot:run
   The server should start on http://localhost:8080.

## API Documentation
Once the application is running, you can use Postman to test the API endpoints. Import the Postman collection provided in the repository to get started quickly with the available REST API endpoints.
