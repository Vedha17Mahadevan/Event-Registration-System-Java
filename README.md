# Event Registration System (Java)

A **Java-based Event Registration System** developed as a **Microproject for Semester 3 (S3)** of **B.Tech Computer Science & Engineering**, under the course **Object-Oriented Programming using Java**.

This application provides a simple GUI-based system for managing events, user registrations, and payments, supporting **Student, Staff, and Admin roles**.

---

## 📌 Project Information

- **Course**: Object-Oriented Programming using Java  
- **Semester**: S3  
- **Project Type**: Microproject  
- **Development Environment**: NetBeans  
- **Programming Language**: Java  
- **Database**: MySQL  
- **GUI Framework**: Java Swing  

---

## 👥 Team Members

| Name | Role | GitHub | LinkedIn |
|------|------|--------|----------|
| Chris Thomas Abraham | Developer | [@ChrisToms14](https://github.com/ChrisToms14) | [Chris Thomas Abraham](https://www.linkedin.com/in/ChrisThomasAbraham) |
| Sradhya Renish | Developer | [@sradhya9](https://github.com/sradhya9) | [Sradhya Renish](https://www.linkedin.com/in/sradhya-renish-74181621b/) |
| Vasundhara S R | Developer | [@Vasundhara-331](https://github.com/Vasundhara-331) | [Vasundhara S R](https://www.linkedin.com/in/vasundhara-s-r/) |
| Vedha Mahadevan | Developer & Tester | [@Vedha17Mahadevan](https://github.com/Vedha17Mahadevan) | [Vedha Mahadevan](http://www.linkedin.com/in/vedha-mahadevan) |

---

## 🧩 Problem Statement

Managing event registrations manually can lead to inefficiencies, data inconsistency, and lack of proper tracking.  
This project aims to provide a **centralized event registration platform** with clear role separation and database-backed storage.

---

## 🎯 Objectives

- Implement **Object-Oriented Programming concepts** using Java
- Design a **role-based event registration system**
- Enable **event creation, update, and deletion** by admins
- Allow users to **view events, register, and confirm payments**
- Integrate **MySQL database connectivity** using JDBC
- Build a **user-friendly GUI** using Java Swing

---

## 🏗️ System Overview

The system supports three main roles:

### 👤 User (Student / Staff)
- Login & Sign Up
- View available events
- View event details
- Register for events
- Confirm payment

### 🛠️ Admin
- Login as admin
- Add new events
- Update event details
- Delete events
- View all registered events

---

## 📐 UML Use Case Diagram

The UML Use Case Diagram illustrates:
- User authentication (Login)
- Event registration flow
- Admin event management
- Payment handling
- Invalid credential handling

<img width="1472" height="1036" alt="UML Diagram" src="https://github.com/user-attachments/assets/ee890227-89de-4b94-90c3-9c35e4af229c" />

---

## 🧠 OOP Concepts Used

- **Classes & Objects**
- **Encapsulation**
- **Abstraction**
- **Separation of Concerns**
- **DAO (Data Access Object) pattern**
- **JDBC for database connectivity**

---

## 🗄️ Database Design

- **Database Name**: `event_reg`
- **Tables include**:
  - Users
  - Events
  - Registrations
- Uses **PreparedStatement** to prevent SQL injection
- Date handling via `java.sql.Date`

---

## 💻 Technologies Used

| Component | Technology |
|--------|-----------|
| Language | Java |
| GUI | Java Swing |
| Database | MySQL |
| IDE | NetBeans |
| Connectivity | JDBC |

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Event-Registration-System-Java.git
   ```
2. Open the project in NetBeans

3. Configure MySQL:
    - Create database `event_reg`
    - Update database credentials in `DatabaseConnection.java`

4. Run the main class:
```bash
WelcomePage.java
```
---

### 📚 Academic Declaration

This project was developed strictly for academic purposes as part of the S3 Microproject and demonstrates the application of Object-Oriented Programming concepts in Java.
