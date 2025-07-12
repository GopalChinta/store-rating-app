# 🏬 Store Rating App

A full-stack role-based web application for rating stores. Built with **React.js**, **Express.js**, and **PostgreSQL/MySQL**.

## 🚀 Features

### 👤 Roles
- **Admin**
  - Add/view users (Admins, Normal Users)
  - Add/view stores
  - View dashboard: total users, stores, and ratings
  - Filter and sort all lists

- **Normal User**
  - Register & Login
  - View/search stores
  - Submit & update ratings (1–5)
  - See own submitted ratings

- **Store Owner**
  - View store ratings and user feedback
  - See average rating of their store

### ✅ Validations
- **Name**: 20–60 characters
- **Address**: max 400 characters
- **Password**: 8–16 chars, 1 uppercase & 1 special character
- **Email**: must be valid

---

## 🧱 Tech Stack

| Layer     | Tech                    |
|-----------|-------------------------|
| Frontend  | React.js, Axios, CSS    |
| Backend   | Node.js, Express.js     |
| Database  | PostgreSQL / MySQL      |
| Auth      | JWT (JSON Web Tokens)   |

---

## 📁 Project Structure

store-rating-app/
├── backend/
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── middlewares/
│ ├── utils/
│ ├── config/
│ ├── app.js
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ ├── utils/
│ │ ├── App.jsx
│ │ └── main.jsx
│ └── public/
├── .env
├── package.json
└── README.md



---

## 🔧 Setup Instructions

### 1. Clone the repo
```
git clone https://github.com/GopalChinta/store-rating-app.git
cd store-rating-app
2. Backend setup

cd backend
npm install
cp .env.example .env  # or manually set DB credentials
npm start
3. Frontend setup

cd ../frontend
npm install
npm run dev
📌 Environment Variables
In backend/.env:

env

PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASS=your_password
DB_NAME=store_rating
JWT_SECRET=your_jwt_secret


📬 Contact
Created by Gopal Chinta
📧 chinthavenugopal2003@gmail.com

🪪 License
MIT License © 2025 Gopal Chinta

