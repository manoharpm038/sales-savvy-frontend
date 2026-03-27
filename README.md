# sales-savvy-app
Full-stack e-commerce web application built using React and Spring Boot, enabling users to browse products, manage cart, and place orders with secure backend APIs.
# 🛒 SalesSavvy - Full Stack E-Commerce Application

## 👨‍💻 Developed By

**Manohara P M**

* Java Full-Stack Developer
* Strong in Java, Spring Boot, React, MySQL


---

## 📌 Project Overview

SalesSavvy is a full-stack e-commerce web application built using **Spring Boot (Backend)** and **React (Frontend)**.
It provides a complete online shopping experience with secure authentication, product management, cart operations, and payment integration.

---

## 🎯 Objective

* Allow users to browse products
* Add items to cart
* Place orders
* Perform secure payments
* Provide admin control for managing the system

---

## 🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL

### Frontend

* ReactJS
* HTML
* CSS
* JavaScript

### Tools & Others

* Git & GitHub
* Postman (API Testing)
* Razorpay (Payment Gateway)

---

## 🏗️ Architecture

The project follows a **layered architecture**:

* Controller Layer → Handles HTTP requests
* Service Layer → Business logic
* Repository Layer → Database operations
* Entity Layer → Database models
* DTO Layer → Data transfer

---

## 🗄️ Database Design

* Designed normalized database schema

* Entities used:

  * User
  * Product
  * ProductImage
  * Category
  * CartItem
  * Order
  * OrderItem
  * JWTToken

* Relationships:

  * One-to-Many
  * Many-to-One

---

## 🔄 ORM & Persistence

* Used **Spring Data JPA** for ORM
* Hibernate automatically maps entities to tables
* All database operations handled using JPA repositories

---

## 🔐 Authentication & Security

* Implemented **JWT Authentication**

  * User registration & login
  * Token generated after login
  * Stored in HTTP-only cookies

### Advantages:

* Prevents XSS attacks
* Stateless authentication
* No server-side session management

---

## 👥 User Roles

### 👤 CUSTOMER

* Browse products
* Add/remove cart items
* Place orders
* Make payments

### 🛠️ ADMIN

* Manage users
* Manage products & categories
* View and manage orders
* Access secured APIs

---

## 🔗 REST API Features

* User Registration & Login
* Product Management APIs
* Category APIs
* Cart APIs
* Order APIs

✔ Follows REST principles
✔ Uses proper HTTP methods (GET, POST, PUT, DELETE)
✔ Returns proper status codes

---

## 📦 Order Management

* Orders and Order Items stored in separate tables
* Order Status:

  * PENDING (default)
  * SUCCESS
  * FAILED

---

## 💳 Payment Integration

* Integrated **Razorpay** payment gateway
* Secure payment verification
* Order status updated after successful payment

---

## 📊 Reporting Features

* Total Revenue
* Daily Orders
* Monthly Orders
* Yearly Orders

(Implemented using custom JPQL queries)

---

## 🚀 Key Highlights

* Full-stack application
* Secure authentication using JWT
* Role-based access control
* Clean architecture design
* Real-world e-commerce workflow
* Scalable backend API design

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/sales-savvy-app.git
cd sales-savvy-app
```

---

### 2️⃣ Backend Setup (Spring Boot)

```bash
cd backend
```

* Configure `application.properties`:

  * MySQL username & password
  * Database URL

```bash
mvn spring-boot:run
```

---

### 3️⃣ Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

---

## 🌐 API Testing

* Use **Postman** to test APIs
* Import API collection (if available)

---

## 📸 Screenshots (Optional)

*Add your UI screenshots here*

---

## 📈 Future Enhancements

* Add product reviews & ratings
* Implement wishlist feature
* Improve UI/UX
* Add email notifications
* Deploy on cloud (AWS/Render)

---

## 🤝 Contribution

Feel free to fork this repository and contribute.

---

## 📬 Contact

**Manohar P M**

* GitHub: https://github.com/your-username
* Email: [your-email@example.com](mailto:your-email@example.com)

---
