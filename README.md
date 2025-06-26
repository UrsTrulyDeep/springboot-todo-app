
---

# 📋 Spring Boot ToDo List API

A simple ToDo List REST API built using **Spring Boot, Spring Data JPA, and MySQL**.

## 🚀 Tech Stack

* **Backend:** Spring Boot
* **Database:** MySQL
* **ORM:** Spring Data JPA
* **Build Tool:** Maven

---

## 🛠️ Features

* ✅ Create a ToDo
* ✅ Retrieve all ToDos
* ✅ Retrieve a ToDo by ID
* ✅ Update a ToDo
* ✅ Delete a ToDo

---

## 📂 Project Structure

```
SpringBootTodoApp/
 └─ src/main/java/com/example/todoapp
      ├─ controller
      ├─ model
      ├─ repository
      ├─ service
 └─ src/main/resources
 └─ pom.xml
```

---

## ⚙️ Configuration

### MySQL Setup

1. Create a database in MySQL:

```sql
CREATE DATABASE tododb;
```

2. Update your `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/tododb
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

## 📮 API Endpoints

| Method | Endpoint          | Description          |
| ------ | ----------------- | -------------------- |
| GET    | `/api/todos`      | Get all ToDos        |
| GET    | `/api/todos/{id}` | Get ToDo by ID       |
| POST   | `/api/todos`      | Create new ToDo      |
| PUT    | `/api/todos/{id}` | Update existing ToDo |
| DELETE | `/api/todos/{id}` | Delete ToDo          |

---

## 🧑‍💻 Running the Project

```bash
# Compile and run the project
mvn spring-boot:run
```

The app will start on:
`http://localhost:8080`

---

## 📫 Contact

Made with ❤️ by Deep Kushwaha

If you like it, drop a ⭐ on the repo!

---
