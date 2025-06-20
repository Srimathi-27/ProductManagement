# ProductManagement
A monolithic Spring Boot application built with layered architecture to manage products with CRUD operations, exception handling, Swagger documentation, and Basic Authentication.

## Features
1. Add, view, update, and delete products
2. Spring Boot + Spring Data JPA + MySQL
3. RESTful API with proper layered structure
4. Swagger UI for API testing
5. Global exception handling
6. Basic authentication security

## Technologies Used
- Java 17
- Spring Boot
- Spring Web, Spring Data JPA
- Spring Security
- MySQL
- Swagger (Springdoc OpenAPI)
- Maven

## Project Structure
model – Product entity
repository – JPA repository
service – Service interface and implementation
controller – REST controller
exception – Custom & global exception handling
config – Security and Swagger setup

## Access Swagger UI
URL: http://localhost:8080/swagger-ui.html
Click Authorize and enter:
Username: admin
Password: admin123

