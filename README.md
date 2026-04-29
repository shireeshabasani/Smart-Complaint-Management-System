# 🏠 Smart Complaint Management System

## 📌 Overview
The Smart Complaint Management System is a full-stack web application designed to streamline the process of submitting and resolving complaints in hostel or institutional environments. It provides a structured workflow for users to raise complaints and for administrators to manage and resolve them efficiently.

This system improves transparency, reduces manual work, and ensures faster grievance resolution.

---

## 🚀 Features

### 👨‍🎓 User / Student Module
- Secure user registration and login
- Submit complaints with description and details
- Track complaint status (Pending / In Progress / Resolved)
- View complaint history

### 🛠️ Admin Module
- Admin dashboard to manage all complaints
- Update complaint status
- View all submitted complaints
- Efficient grievance handling system

---

## 🛠️ Tech Stack

Frontend: React.js, HTML5, CSS3, JavaScript (ES6+)  
Backend: Node.js, Express.js  
Database: PostgreSQL  
Architecture: REST API (Client-Server Model)

---

## 🏗️ System Architecture

React Frontend → Node.js + Express Backend → PostgreSQL Database

---




## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
git clone https://github.com/shireeshabasani/Smart-Complaint-Management-System.git

---

### 2️⃣ Backend Setup
cd backend
npm install

Create .env file:
PORT=5000
DATABASE_URL=your_postgresql_connection_string
JWT_SECRET=your_secret_key

Run backend:
npm start

---

### 3️⃣ Frontend Setup
cd frontend
npm install
npm run dev

---

### 4️⃣ Database Setup
CREATE DATABASE complaint_system;

Import database.sql into PostgreSQL.

---

## 📡 API Endpoints

POST /api/register → Register user  
POST /api/login → User login  
POST /api/complaint → Create complaint  
GET /api/complaints → Get all complaints  
PUT /api/complaint/:id → Update complaint status  

---

## 📈 Future Improvements
- Email & SMS notifications
- Real-time chat system
- File upload support
- Mobile app version
- AI-based complaint classification

---

## 👨‍💻 Developer
Shireesha Basani  
GitHub: https://github.com/shireeshabasani

---

## 📜 License
This project is for educational purposes only.

---

## ⭐ Key Highlights
- Full-stack React + Node + PostgreSQL project
- Real-world complaint management system
- REST API integration
- Clean and structured workflow
- Internship/placement-ready project
