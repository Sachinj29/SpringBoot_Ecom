# 🛒 E-commerce Web Application

An end-to-end E-commerce platform that allows users to browse, search, add to cart, and purchase products — with full backend support for managing items and inventory.

---

## 🚀 Tech Stack

**Frontend:**
- ![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
- ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
- ![CSS3](https://img.shields.io/badge/CSS-3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend:**
- ![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
- ![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
- ![Spring MVC](https://img.shields.io/badge/Spring_MVC-Web-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
- ![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-ORM-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
- ![REST API](https://img.shields.io/badge/REST_API-Enabled-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Database:**
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-336791?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 🧩 Features

### 👥 User Side
- 🔍 Browse and search for products
- 🛒 Add items to the cart
- 💳 Place orders securely
- 🗃️ View product details

### 🛠️ Admin Side
- ✅ Full **CRUD operations** on products
- 📦 Manage inventory and stock
- 🧾 Order processing logic (future scope)

---

## 📁 Project Structure

### Frontend (`/frontend`)
Built using **React** and **JavaScript**, styled with **CSS**.

- Product listing page
- Product details page
- Cart and Checkout
- API integration using `fetch`/`Axios`

### Backend (`/backend`)
Spring Boot RESTful service structured into:

- **Controller**: Exposes REST APIs
- **Service Layer**: Business logic
- **Repository**: Spring Data JPA for DB access
- **Model**: JPA Entities

---

## 🧰 Tools Used

| Purpose        | Tool            |
|----------------|-----------------|
| Code Editor (Frontend) | VS Code          |
| IDE (Backend)          | IntelliJ IDEA    |
| Database GUI           | pgAdmin          |
| API Testing            | Postman (Optional) |

---

## 🏁 Getting Started

### ✅ Prerequisites
- Node.js & npm
- Java 17+
- PostgreSQL
- Maven



### 🔧 Configure database in application.properties :

spring.datasource.url=jdbc:postgresql://localhost:5432/your_datbase_name
spring.datasource.username=your_username
spring.datasource.password=your_password

