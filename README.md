# 📘 LMS Backend API – Node.js + Express + MongoDB

A fully functional **Learning Management System (LMS)** backend built with **Node.js**, **Express**, and **MongoDB**.  
The API supports authentication, course management, interactive learning features, and admin operations.  
All endpoints are tested and documented using **Postman**.

---

## 🚀 Features

### 🔐 Authentication & User Management
- User registration  
- Email-based activation  
- Login & Logout  
- JWT authentication  
- Access & Refresh tokens  
- Load authenticated user  
- Social auth support

---

### 🎓 Course Management
- Create new courses (Admin)  
- Edit existing courses  
- View single course (public)  
- Get all courses (public)  
- Access full course content (enrolled users)  
- Retrieve all courses (Admin dashboard)

Each course includes:
- Title, description, level  
- Videos & lessons  
- External links  
- Benefits & prerequisites  
- Reviews  
- Q&A section

---

### 💬 Interactive Learning Tools
- Students can ask questions on lessons  
- Instructors/Admins can reply  
- Students can submit course reviews  
- Admins can reply to reviews

---

## 🛠 Tech Stack
- **Node.js**  
- **Express.js**  
- **MongoDB & Mongoose**  
- **JWT Authentication**  
- **Postman** for testing

---

## 📂 Project Structure
/src
   /controllers
   /routes
   /models
   /middlewares
   /utils
server.js


---

## 🧪 API Testing
All API endpoints are available in a **Postman Collection**, including:
- Auth routes  
- Course routes  
- Review routes  
- Q&A routes  
- Admin routes

---

## 📌 Postman Collection
You can import the included Postman JSON file to test all routes easily.

---

## 🛡 Security
- Password hashing with bcrypt  
- JWT-based authentication  
- Protected routes for admin & users


