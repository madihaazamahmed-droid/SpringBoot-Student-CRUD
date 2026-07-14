# SpringBoot-Student-CRUD

## Project Overview

SpringBoot-Student-CRUD is a Student Management System developed using Spring Boot. This application performs CRUD (Create, Read, Update, Delete) operations to manage student records with MySQL database integration.

## Features

- Add new student records
- View all student details
- View student details by ID
- Update student information
- Delete student records
- RESTful API implementation
- MySQL database connectivity

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- REST API
- Postman

## Project Architecture

Controller Layer
        |
        ↓
Service Layer
        |
        ↓
Repository Layer
        |
        ↓
Database (MySQL)

## Project Structure

src/main/java/com/example/student

controller
- StudentController.java

service
- StudentService.java

repository
- StudentRepository.java

entity
- Student.java


## Installation & Setup

### Clone Repository

git clone https://github.com/yourusername/SpringBoot-Student-CRUD.git


### Database Configuration

Update application.properties file:

spring.datasource.url=jdbc:mysql://localhost:3306/studentdb

spring.datasource.username=root

spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update

spring.jpa.show-sql=true


## Run Application

mvn spring-boot:run


Application runs on:

http://localhost:8080


## REST API Endpoints

GET      /students          - Get all students

GET      /students/{id}     - Get student by ID

POST     /students          - Create new student

PUT      /students/{id}     - Update student

DELETE   /students/{id}     - Delete student


## API Testing

API endpoints are tested using Postman.


## Author

Madiha Azam Ahmed
