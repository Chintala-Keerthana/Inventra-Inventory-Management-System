# Inventra – Intelligent Inventory Management System
Inventra Inventory Management System with milestones and project report

## Project Overview

Inventra is an Intelligent Inventory Management System developed using **Spring Boot** for the backend and **HTML, CSS, and JavaScript** for the frontend. The system is designed to manage inventory efficiently by providing role-based access for **Admin** and **Employee** users. It supports essential inventory operations such as stock management, user authentication, and dashboard-based monitoring.

This project is primarily intended for **academic use, internship submissions, and learning purposes**, focusing on practical exposure to backend–frontend integration and RESTful API development.

## Key Features

* Role-based user access (Admin and Employee)
* Secure user registration and login
* Inventory tracking and stock management
* Low-stock monitoring for proactive decision-making
* Separate dashboards for Admin and Employee users
* Frontend–backend communication using REST APIs
  
## Technology Stack

### Backend

* Java
* Spring Boot
* Spring Data JPA
* RESTful APIs

### Frontend

* HTML
* CSS
* JavaScript

### Database

* MySQL
* MySQL Workbench

## Project Structure

* Backend developed using **Spring Boot**
* Frontend static files located at:- src/main/resources/static
* Database managed using **MySQL Workbench**
* REST APIs used for interaction between frontend and backend

**Note:** The original package name `com.inventory.inventory-backend` was invalid. The correct package name used in this project is:
com.inventory.inventory_backend
## System Modules

### 1. User Management Module

* User registration
* User login
* Role-based access control (Admin / Employee)
* OTP-based password reset

### 2. Inventory Management Module

* Add new inventory items
* Update inventory quantity
* View available stock
* Track low-stock items
* Categorize inventory (e.g., medicines, equipment, supplies)

### 3. Dashboard & Access Module

* Admin Dashboard
* Employee Dashboard
* Role-based redirection after login
* Session handling using browser **localStorage**

---

## User Roles & Permissions

###  Admin

* Add and update inventory items
* View complete stock details
* Monitor low-stock alerts
* Access Admin Dashboard

###  Employee

* View inventory items
* Check stock availability
* Access Employee Dashboard

## Database Details

* **Database Name:** `inven_db`
* **Database Tool:** MySQL Workbench
* **Main Table:** `users`
* Inventory-related tables store item details, quantity, and category

## How to Run the Project

### Step 1: Start the Database

1. Open MySQL Workbench
2. Start the MySQL server
3. Ensure the database `inven_db` exists

### Step 2: Run the Backend

1. Open the project in an IDE (IntelliJ IDEA or Eclipse)
2. Run the main application file:
   InventoryBackendApplication.java
   **OR** using terminal:
   mvn spring-boot:run
   
### Step 3: Access the Application

* Open a web browser and navigate to:
  http://localhost:8080/login.html
  
## Security Considerations

* Session management is handled using browser **localStorage**
* Spring Security and JWT authentication are **not implemented**

⚠️ This application is **not recommended for production use** and is intended only for learning and academic demonstrations.

## Team Contribution

This project is developed as a **team project**, with responsibilities divided as follows:

* Backend development using Spring Boot
* Frontend development using HTML, CSS, and JavaScript
* Code collaboration and version control using GitHub

## Purpose of the Project

* Academic project submission
* Internship evaluation
* Hands-on learning of Spring Boot and REST APIs
* Understanding core concepts of Inventory Management Systems
* Experience with team collaboration using GitHub

## References

* Apache Maven Documentation
* Spring Boot Maven Plugin Reference Guide
* Spring Web
* Spring Data JPA
* MySQL Documentation

**End of Document**
