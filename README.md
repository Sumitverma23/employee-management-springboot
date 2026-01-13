# 📌 Employee Management System
## 🏢 Task Provided By

### Mindprove Technologies Pvt Ltd

## 📌 Project Description

The Employee Management System is a Spring Boot REST API application developed using Java, Spring Boot, Spring Security, JPA/Hibernate, and MySQL.

It allows administrators to manage employee records efficiently by performing CRUD operations and ensures role-based access control using Spring Security.

The system includes proper validation, exception handling, and secure password management, following industry best practices.
## 🛠️ Technologies Used

Java 17

Spring Boot 3.x

Spring Security

Spring Data JPA

MySQL

Maven

IntelliJ IDEA


## ✨ Features

Admin Role

➕ Create new employee

✏️ Update employee details

❌ Delete employee

User Role

📋 View all employees

🔍 Search employee by ID

Security & Validation

🔐 Role-based access (ADMIN / USER)

✅ Input validation (@NotBlank, @Email, @Positive)

🔒 Password encryption using BCryptPasswordEncoder

Exception Handling

404 Not Found for missing resources

400 Bad Request for validation errors

500 Internal Server Error for unhandled exceptions

## 🧠 Concepts Covered

Spring Boot REST API development

Layered architecture (Controller → Service → Repository → Entity)

Role-based authentication and authorization (Spring Security)

Password encryption using BCrypt

Validation using Jakarta Bean Validation

Global exception handling using @RestControllerAdvice

JPA / Hibernate integration with MySQL
