Spring Boot Task Manager

A simple RESTful Task Manager backend built with Spring Boot.  
It allows users to create, read, update, and delete tasks using standard HTTP methods.  
The app uses an in-memory H2 database, making it lightweight and easy to test locally.

---------

Features

- Create, read (all/by ID), update, and delete tasks
- DTO-based request/response model
- Custom exception handling (e.g., Task not found)
- Service and Repository layer separation
- Pre-configured with H2 

---------

Tech Stack

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database (in-memory)
- Maven
- IntelliJ IDEA

---------

API Endpoints

| Method | Endpoint             | Description              |
|--------|----------------------|--------------------------|
| POST   | `/api/tasks`         | Create a new task        |
| GET    | `/api/tasks`         | Get all tasks            |
| GET    | `/api/tasks/{id}`    | Get a task by ID         |
| PUT    | `/api/tasks/{id}`    | Update a task by ID      |
| DELETE | `/api/tasks/{id}`    | Delete a task by ID      |

---------
