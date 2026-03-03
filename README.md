# Evangadi Forum

[![Frontend](https://img.shields.io/badge/Frontend-React-blue)](https://forum.abdurehman.com)  


Evangadi Forum is a **full-stack Question and Answer web application** inspired by community-driven discussion platforms. The application enables users to ask questions, provide answers, vote on responses, and engage in structured discussions within a secure and authenticated environment.

The system is designed with a clean RESTful architecture, focusing on scalability, security, and maintainability.

---

## 🌐 Demo

-  live: [https://forum.abdurehman.com](https://forum.abdurehman.com)

## 🚀 Features
- User registration and authentication (JWT)
- Ask and answer questions
- Upvote and downvote answers
- Comment on answers
- Pagination for questions and answers
- User profile association with content
- Protected routes for authenticated users
- RESTful API architecture

---

## 🛠 Tech Stack

**Frontend**
- React
- HTML5, CSS3
- JavaScript (ES6+)

**Backend**
- Node.js
- Express.j
- RESTful API architecture

**Database**
- MySQL

**Authentication & Tools**
- JWT Authentication
- Git & GitHub
- Postman

---

## 📂 Project Structure

 ```bash
evangadi-forum/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── routes/
│   ├── models/
│   ├── config/
│   ├── app.js
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── context/
│   │   └── App.jsx
│   ├── public/
│   └── main.jsx
│
├── database/
│   └── schema.sql
│
├── .env
├── README.md
└── package.json
```
## 📂 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/mikretadesse/evangadi-forum-G3.git
    cd evangadi-forum-G3
   ```
 2. Backend Setup

   ```bash
   cd backend
   npm install
   nodemon server.js
   ```
3. Frontend Setup
     ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

## 📸 Screenshots

![Landing Page](./screenshots/carts.png)  
![Home Page](./screenshots/home.png)  
![Qusstion Page](./screenshots/mac.png)  
![Answer Page](./screenshots/support.png)  



