# 📋 TaskAPI

A RESTful API for task management, developed as an academic project for the Backend Web Development course.

## 💡 About the Project

This API provides complete task management functionality, including create, read, update, and delete operations. Each task contains information such as name, due date, and responsible person.

## 🚀 Features

- **Task creation** with fields: name, due date, and responsible person
- **Complete listing** of all registered tasks
- **Update** of existing tasks
- **Removal** of tasks from the system

## 🛠️ Technologies Used

- **Java** with Spring Boot
- **Spring Data JPA** for data persistence
- **MySQL** as relational database
- **Maven** for dependency management

## 📦 Prerequisites

- Java JDK 11 or higher
- Maven 3.6+
- MySQL Server 5.7 or higher

## ⚙️ Setup and Execution

The API will be available at `http://localhost:8080`

## 📡 API Endpoints

### 🟢 GET /tarefas
Returns all registered tasks

### 🟡 POST /tarefas
Creates a new task
```json
{
    "nome": "Task name",
    "dataEntrega": "2023-12-31",
    "responsavel": "Responsible person name"
}
```

### 🔵 PUT /tarefas/{id}
Updates an existing task

### 🔴 DELETE /tarefas/{id}
Removes a task from the system

## 🏗️ Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── taskapi/
│   │           ├── controller/
│   │           ├── model/
│   │           ├── repository/
│   │           └── service/
│   └── resources/
│       └── application.properties
```
