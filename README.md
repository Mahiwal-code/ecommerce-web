# 🛒 E-Commerce Fullstack Project (Java 23 + Spring Boot 3 + React)

This is a **full-stack e-commerce web application** built with **Java 23, Spring Boot 3, React, and PostgreSQL/MySQL**.  
The backend provides RESTful APIs for category, product, cart, order, and authentication.

---

## 🚀 Features Implemented
- ✅ Category CRUD with pagination & sorting  
- ✅ Product CRUD linked with categories (discount & special price auto-calculation)  
- ✅ Global exception handling  
- ✅ DTO mapping with ModelMapper  

---

## 🔮 Upcoming Features
- 🛒 Cart module  
- 📦 Orders module  
- 👤 Authentication & Authorization (JWT)  
- 🏠 Address Management  
- 🎨 Frontend (React) integration  

---

## 🛠️ Tech Stack
- **Backend:** Java 23, Spring Boot 3, Spring Data JPA, Hibernate  
- **Database:** PostgreSQL / MySQL  
- **Frontend (Planned):** React, TailwindCSS  
- **Tools:** Postman (API testing), ModelMapper, Lombok  

---

## 📂 API Endpoints (tested via Postman)
- `GET /api/public/categories` → Get all categories (with pagination/sorting)  
- `POST /api/public/categories` → Create a category  
- `PUT /api/admin/categories/{id}` → Update a category  
- `DELETE /api/admin/categories/{id}` → Delete a category  
- `POST /api/admin/categories/{categoryId}/product` → Add a product under a category  

---


