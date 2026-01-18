
# 🛒 EazyStore – Full Stack E-Commerce Application

EazyStore is a full-stack e-commerce web application built using **Spring Boot** for the backend and **Vite + React** for the frontend.  
The project demonstrates real-world full-stack architecture with REST APIs, database integration, and a modern responsive UI.

---

## 📌 Features

- User authentication (login)
- Product listing
- Database integration with MySQL
- RESTful APIs
- Modern responsive frontend
- Clean separation of frontend & backend

---

## 🛠 Tech Stack

### Backend
- Java  
- Spring Boot  
- Spring Data JPA  
- Hibernate  
- MySQL  
- Maven  

### Frontend
- Vite  
- React  
- HTML5  
- CSS3  
- JavaScript  

### Tools
- Git & GitHub  
- VS Code  
- MySQL Workbench  

---

## 📁 Project Structure

```

fullstack-main/
│
├── BACKEND/          # Spring Boot backend
│   ├── src/
│   ├── pom.xml
│
├── FRONTEND/         # Vite + React frontend
│   ├── eazystore-ui/
│       ├── src/
│       ├── package.json
│
└── README.md

````

---

## 🚀 How to Run the Project

### 1️⃣ Backend Setup

#### Prerequisites
- Java 17+
- Maven
- MySQL

#### Steps
```bash
cd BACKEND
mvn spring-boot:run
````

Backend runs at:

```
http://localhost:8080
```

---

### 2️⃣ Frontend Setup

```bash
cd FRONTEND/eazystore-ui
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## 🗄 Database Configuration

* Database: **MySQL**
* Schema name: **jewelicious**

```sql
CREATE DATABASE jewelicious;
```

Configure database credentials in:

```
BACKEND/src/main/resources/application.properties
```

---

## 📸 Screenshots

*Add screenshots of Home page, Product page, etc.*

---

## 📌 Future Enhancements

* User registration
* Cart & checkout
* Payment gateway integration
* Admin dashboard
* JWT authentication

---

## 🤝 Credits

Inspired by open-source projects from the GitHub community.
Modified, extended, and maintained by **Ketharnath R**.

---

## 📄 License

This project is created for **educational purposes**.

```


