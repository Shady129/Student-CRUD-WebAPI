# 🎓 ASP.NET Core Student CRUD Web API

---

## 🚀 Project Overview

This is a simple **ASP.NET Core Web API** project that demonstrates:

- ✔ CRUD Operations (Create, Read, Update, Delete)
- ✔ DTO Usage (Create / Read / Update)
- ✔ Client-Server Communication
- ✔ Proper HTTP Status Codes
- ✔ Async/Await in Client Side
- ✔ Clean and Simple Structure

This project was built as my **first Web API project** to understand how APIs work in real-world applications.

---

## 🏗 Architecture Structure

### 🔹 Server Side (Web API)

- Student Model
- DTOs:
  - StudentCreateDto
  - StudentReadDto
  - StudentUpdateDto
- StudentController
- In-Memory Storage (for demo purposes)

---

### 🔹 Client Side (Console App)

- Application Layer
- StudentService Layer
- StudentClient (HTTP Communication)
- Async API Calls

---

## 📌 API Endpoints

| Method | Endpoint            | Description              |
|--------|--------------------|--------------------------|
| GET    | /api/Student       | Get all students         |
| GET    | /api/Student/{id}  | Get student by ID        |
| POST   | /api/Student       | Create new student       |
| PUT    | /api/Student/{id}  | Update student           |
| DELETE | /api/Student/{id}  | Delete student           |

---

## 🧠 Concepts Learned

- ✔ RESTful API Principles
- ✔ DTO Pattern
- ✔ ActionResult & Status Codes
- ✔ CreatedAtAction()
- ✔ 204 NoContent Handling
- ✔ Mapping Between Model and DTO
- ✔ HttpClient Usage
- ✔ Separation of Concerns

---

## ⚠ Note

This project uses **In-Memory List** instead of a database  
for learning and demonstration purposes only.

---

## 🛠 Technologies Used

- ASP.NET Core Web API
- C#
- .NET
- HttpClient
- Console Application

---

## 📈 Future Improvements (Optional)

- Add Database (EF Core)
- Add Validation Attributes
- Implement Repository Pattern
- Add Dependency Injection for Services
- Add Logging

---

## 👨‍💻 Author

Shady Mahmoud  
Backend Developer (ASP.NET Core)

---

⭐ If you like this project, feel free to star the repository.
