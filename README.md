# 🏠 Smart Complaint Management System

## 📌 Overview
The **Smart Complaint Management System** is a full-stack web application designed to streamline the process of submitting and resolving complaints in hostel or institutional environments. It provides a structured workflow for users to raise complaints and for administrators to manage and resolve them efficiently.

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

- **Frontend:** React.js, HTML5, CSS3, JavaScript (ES6+)
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Architecture:** REST API (Client-Server Model)

---

## 🏗️ System Architecture
React Frontend → Node.js + Express Backend → PostgreSQL Database


---


---

## 📂 Project Structure

bash id="structfinal1"
Smart-Complaint-Management-System/
│
├── backend/
│   ├── controller/
│   ├── routes/
│   ├── middleware/
│   ├── db.js
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── components/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── public/
│   ├── package.json
│   ├── vite.config.js
│   └── tailwind.config.js
│
├── images/
│   ├── login.png
│   ├── signup.png
│   ├── studentDashboard.png
│   ├── studentComplaint.png
│   ├── wardenDashboard.png
│   └── createComplaint.png
│
├── database.sql
├── docker-compose.yml
└── README.md



⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/shireeshabasani/Smart-Complaint-Management-System.git


2️⃣ Backend Setup
cd backendnpm install
Create .env file:
PORT=5000DATABASE_URL=your_postgresql_connection_stringJWT_SECRET=your_secret_key
Run backend:
npm start

3️⃣ Frontend Setup
cd frontendnpm installnpm run dev

4️⃣ Database Setup
CREATE DATABASE complaint_system;
Import database.sql file into PostgreSQL.

📡 API Endpoints
MethodEndpointDescriptionPOST/api/registerRegister userPOST/api/loginUser loginPOST/api/complaintCreate complaintGET/api/complaintsGet all complaintsPUT/api/complaint/:idUpdate complaint status



📈 Future Improvements


Email & SMS notifications


Real-time chat between user and admin


File upload for complaint proof


Mobile application version


AI-based complaint classification system



👨‍💻 Developer
Shireesha Basani
GitHub: shireeshabasani

📜 License
This project is for educational purposes only.

⭐ Key Highlights


Full-stack MERN-style architecture (React + Node + PostgreSQL)


Real-world complaint management system


REST API integration


Clean UI with structured workflow


Beginner-friendly but industry-relevant project


