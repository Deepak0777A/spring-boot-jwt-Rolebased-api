🔐 JWT Authentication & Authorization – Spring Boot REST API
📌 About

A Spring Boot REST API that implements JWT-based authentication with role-based authorization, BCrypt password encryption, and stateless security.
The application follows clean architecture principles and exposes secure REST endpoints tested using Postman.

🚀 Features

User Registration & Login

JWT Token Generation & Validation

Role-Based Authorization (USER, ADMIN)

Password Encryption using BCrypt

Stateless Authentication (No Sessions)

Input Validation using DTOs

Global Exception Handling

RESTful API Design

Tested with Postman

🛠️ Tech Stack

Java

Spring Boot

Spring Security

JWT (JSON Web Token)

Spring Data JPA

Hibernate

MySQL

BCrypt Password Encoder

Maven

Postman

🔐 Authentication Flow

User registers with username, password, and role

Password is encrypted using BCrypt before saving

User logs in with credentials

JWT token is generated and returned

Token is sent in Authorization header for secured APIs

Authorization: Bearer <JWT_TOKEN>

📂 Project Structure
src/main/java
 └── com.example.jwt
     ├── controller
     ├── service
     ├── repository
     ├── model
     ├── dto
     ├── security
     └── exception

📌 API Endpoints
🔹 Register User
POST /register

{
  "username": "deepak",
  "password": "123456",
  "role": "USER"
}

🔹 Login User
POST /login

{
  "username": "deepak",
  "password": "123456"
}


➡ Returns JWT Token

🔐 Secured Endpoint Example
GET /api/user/profile


Header:

Authorization: Bearer <JWT_TOKEN>

⚙️ Configuration
application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/jwt_db
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

jwt.secret=your_secret_key
jwt.expiration=86400000

🧪 Testing

APIs tested using Postman

Invalid credentials return 401 Unauthorized

Duplicate username returns 409 Conflict

Validation errors return 400 Bad Request

🧠 Key Learnings

Implementing stateless authentication using JWT

Securing REST APIs with Spring Security

Applying role-based authorization

Using DTOs for request validation

Clean separation of concerns

📌 Future Enhancements

Refresh Token Implementation

Email Verification

Forgot Password Flow

OAuth2 Integration

Rate Limiting

👨‍💻 Author

Deepak
Backend Developer | Java | Spring Boot
