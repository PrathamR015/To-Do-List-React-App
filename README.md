# 📝 To-Do List React App

A **full-stack To-Do List application** built using **React, Node.js, Express, and MongoDB**.
This app helps users efficiently manage daily tasks with authentication, email support, and a clean UI.

---

## 🚀 Project Overview

The **To-Do List React App** allows users to:

* Create, update, and delete tasks
* Mark tasks as completed
* Register and log in securely using JWT authentication
* Receive email-related functionality using Gmail integration
* Store tasks persistently using MongoDB

The project follows a **frontend–backend separation**, making it scalable and easy to maintain.

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript (ES6)
* Axios

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication
* Nodemailer
* dotenv

---

## 📂 Project Structure

```
To-Do-List-React-App/
│
├── frontend/        # React frontend
│   ├── src/
│   └── package.json
│
├── backend/         # Node + Express backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## 📥 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/PrathamR015/To-Do-List-React-App.git
```

---

### 2️⃣ Install Frontend Dependencies

```bash
cd frontend
npm install
```

---

### 3️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

---

## ⚙️ Configuration

Create a `.env` file inside the **backend** directory and add the following:

```env
MONGO_URI=your_mongodb_connection_string
GMAIL_USERNAME=your_gmail_address
GMAIL_PASSWORD=app_password_generated_from_google
PORT=8000
JWT_SECRET=your_secret_key
```

### 🔐 Notes:

* Use **MongoDB Atlas** or a local MongoDB instance
* Keep `.env` file private (do not commit it)

---

## ▶️ Run the Application

### Start Backend Server

```bash
cd backend
nodemon server
```

Server runs on:

```
http://localhost:8000
```

---

### Start Frontend Server

```bash
cd frontend
npm start
```

Frontend runs on:

```
http://localhost:3000
```

---

## ✨ Features

* ✅ User authentication (Register / Login)
* 🗂️ Create, update, delete tasks
* ☑️ Mark tasks as completed
* 📧 Email support using Gmail
* 🔐 Secure JWT-based authentication
* 📦 MongoDB database integration
* 🎨 Clean and responsive UI

---

## 📌 Future Enhancements

* Task priority levels
* Due date & reminders
* Drag-and-drop task ordering
* Dark mode
* Deployment to cloud platforms



