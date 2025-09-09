# 📚 Library Management API

A **Spring Boot REST API** to manage a library of books.  
Designed for learning, testing, and as a starter project for a library management system.

---

## 🚀 Features

- CRUD operations for books
- H2 in-memory database for testing
- Spring Data JPA integration
- REST API endpoints
- H2 console for database management

---

## 🛠 Technologies Used

- **Java 17**
- **Spring Boot 3.5.5**
- **Spring Data JPA**
- **H2 Database**
- **Maven**
- **Postman** (for API testing)

---

## ⚙️ Setup & Run

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/library-management-api.git
Navigate to the project folder:

bash
Copy code
cd library-management-api
Build & run the project:

bash
Copy code
./mvnw spring-boot:run
Access API:

arduino
Copy code
http://localhost:8080
Access H2 console (for DB testing):

bash
Copy code
http://localhost:8080/h2-console
JDBC URL: jdbc:h2:mem:librarydb

Username: sa

Password: (leave empty)

📌 API Endpoints
Method	Endpoint	Description
GET	/books	Get all books
GET	/books/{id}	Get book by ID
POST	/books	Add a new book
PUT	/books/{id}	Update a book
DELETE	/books/{id}	Delete a book

🖼 Screenshots
H2 Database Console

Sample API Test (Postman)

📄 License
This project is licensed under the MIT License.

