# 🎓 Smart Student Record and Analytics System

## 📌 Project Overview

This project is a full-stack web application designed to manage and analyze student records efficiently. It allows users to perform CRUD operations, search and filter data, view analytics, and handle large datasets using pagination.

---

## 🚀 Tech Stack

### 🔹 Backend

* Spring Boot
* Spring Data JPA
* MySQL Database
* REST APIs

### 🔹 Frontend

* React (TypeScript)
* Tailwind CSS
* Fetch API

---

## ⚙️ Features

### ✅ Core Management

* Add student records
* View all students
* Delete student records

### 🔍 Search & Filter

* Search students by name
* Filter students by marks range

### 📊 Analytics

* Department-wise student count
* Average marks calculation

### 📄 Pagination & Sorting

* Paginated data display
* Sorting based on marks

### ⚠️ Exception Handling

* Global exception handling using Spring Boot

---

## 🧱 Project Structure


student-management-system/
│
├── backend/        # Spring Boot Backend
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   └── resources/
│
├── frontend/       # React Frontend
│   ├── components/
│   ├── api/
│   └── pages/




 🔗 API Endpoints

| Method | Endpoint                        | Description      |
| ------ | ------------------------------- | ---------------- |
| GET    | /students                       | Get all students |
| POST   | /students                       | Add new student  |
| DELETE | /students/{id}                  | Delete student   |
| GET    | /students/search?name=          | Search by name   |
| GET    | /students/filter?min=&max=      | Filter by marks  |
| GET    | /students/page?page=&size=      | Pagination       |
| GET    | /students/analytics/average     | Average marks    |
| GET    | /students/analytics/departments | Dept-wise count  |

---

## ▶️ How to Run

### 🔹 Backend

1. Open Spring Boot project in Eclipse/IDE
2. Configure MySQL in `application.properties`
3. Run `StudentApplication.java`
4. Backend runs on:

```
http://localhost:8080
```

---

### 🔹 Frontend

1. Open frontend folder in VS Code
2. Install dependencies:


npm install


3. Run project:


npm run dev


4. Open:


http://localhost:5173


## 🗄️ Database Setup

sql
CREATE DATABASE student_db;

Update `application.properties`:

spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=root
spring.datasource.password=your_password




## 🔄 Architecture
text
Frontend (React)
       ↓
REST API (Controller)
       ↓
Service Layer
       ↓
Repository (JPA)
       ↓
MySQL Database




## 🎯 Key Concepts Used

* RESTful API Design
* Layered Architecture
* JPA & Hibernate
* Pagination & Sorting
* Aggregate Functions (COUNT, AVG)
* React Hooks (useState, useEffect)



## 👨‍💻 Author

* Manaswi Ganji
* M.Aruna Grace
* Hasini peddi
* Sreeja
* Tejaswi Priyank

---

## 📌 Conclusion

This project demonstrates a complete full-stack implementation with efficient data handling, clean architecture, and user-friendly interface, suitable for real-world applications.
