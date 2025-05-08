# Student Management System - Spring Boot CRUD App

This is a simple backend project developed using **Spring Boot** and **MySQL**. It allows you to perform CRUD operations on student data via RESTful APIs.

## 🔧 Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Postman (for testing)

## 📌 Features
- Add, update, view, and delete student records
- MySQL database integration
- Standard MVC architecture (Controller, Service, Repository)

## 📂 API Endpoints
- `GET /students` – Get all students
- `POST /students` – Add a new student
- `PUT /students/{id}` – Update student
- `DELETE /students/{id}` – Delete student

## ⚙️ How to Run
1. Clone this repo
2. Create a MySQL DB: `student_directory`
3. Update your MySQL credentials in `application.properties`
4. Run the app using `mvn spring-boot:run`
5. Test using Postman

## 👩‍💻 Author
Nishtha Gupta
