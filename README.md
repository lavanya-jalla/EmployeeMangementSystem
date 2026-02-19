## Employee Management System (EMS) – REST API
A Spring Boot based RESTful API for managing employees.
This project demonstrates CRUD operations using Spring Boot, Spring Data JPA, and MySQL.

## Tech Stack
Java 17
Spring Boot 3
Spring Data JPA
Hibernate
MySQL 8
Maven
Lombok

## Architecture Used
Controller Layer
        ↓
Service Layer
        ↓
DAO Layer
        ↓
Database (MySQL)

## Project Structure
RestApiCrudEMS
│
├── controller
│     └── EmployeeController.java
│
├── service
│     └── EmployeeService.java
│
├── dao
│     └── EmployeeDAO.java
│
├── entity
│     └── Employee.java
│
└── RestApiCrudEmsApplication.java

## Features
Add Employee
View All Employees
View Employee by ID
Update Employee Details
Delete Employee
DAO Pattern Implementation
MySQL Database Integration
RESTful API Design

## Database Setup
Create database:
CREATE DATABASE emdir;

## REST API Endpoints

| Method | Endpoint            | Description        |
| ------ | ------------------- | ------------------ |
| POST   | /api/employees      | Create Employee    |
| GET    | /api/employees      | Get All Employees  |
| GET    | /api/employees/{id} | Get Employee by ID |
| PUT    | /api/employees/{id} | Update Employee    |
| DELETE | /api/employees/{id} | Delete Employee    |

## Author
Lavanya
B.Tech Computer Science Engineering

