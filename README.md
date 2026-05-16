# Employee Management System

A basic Spring Boot project to perform CRUD operations on employee data.

## Technologies Used
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Postman

## Features
- Add Employee
- View All Employees
- View Employee by ID
- Update Employee
- Delete Employee

## API Endpoints

| Method | Endpoint | Description |
|------|------|------|
| POST | /employees | Add employee |
| GET | /employees | Get all employees |
| GET | /employees/{id} | Get employee by ID |
| PUT | /employees/{id} | Update employee |
| DELETE | /employees/{id} | Delete employee |

## How to Run
1. Create database `employee_db`
2. Update `application.properties`
3. Run the application
4. Test APIs using Postman

## Author
Mohd Ismail