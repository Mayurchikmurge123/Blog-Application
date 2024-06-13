# Spring Boot Blog Application

## Overview
This project is a comprehensive REST API for a Blog Application, built using Spring Boot, Spring Security, JWT, Spring Data JPA, and MySQL database. 

## Features
- **REST Basics**: Understand Resource, Sub-resource, URI, HTTP methods, and HTTP status codes.
- **CRUD REST APIs**: Create, Read, Update, and Delete blog posts.
- **Pagination and Sorting**: Implement REST APIs for pagination and sorting.
- **User Authentication**: Build REST APIs for Login/Signin and Signup using JWT.
- **Lombok**: Simplify Java code with Lombok annotations.
- **DTOs**: Use Data Transfer Objects (DTOs) for cleaner code.
- **Exception Handling**: Implement robust REST API exception handling.
- **Validation**: Validate REST API requests using Spring Boot.
- **Spring Security**: Secure your application with Spring Security, including in-memory and DB authentication and authorization.
- **Role-based Security**: Secure REST APIs based on user roles.
- **Spring Data JPA**: Write query methods, and implement one-to-many and many-to-many JPA mappings.
- **Testing with Postman**: Test REST APIs using Postman REST Client.
- **JWT Integration**: Learn what JWT is, how it works, and how to configure it in Spring Security.
- **API Versioning**: Implement REST API versioning using four important strategies.
- **Deployment**: Deploy the application on AWS Cloud.
- **Docker**: Containerize the application using Docker.
- **Spring Annotations**: Utilize various Spring and Spring Boot annotations throughout the project.

## Getting Started
### Prerequisites
- Java 11 or higher
- Maven or Gradle
- MySQL database
- Docker (optional for containerization)
- AWS account (optional for deployment)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Mayurchikmurge123/Blog-Application.git
   cd Blog-Application
   ```
2. Update the application properties with your MySQL database configuration:
   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/blog_db
   spring.datasource.username=root
   spring.datasource.password=*******
   ```
3. Build and run the application:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
       
   
