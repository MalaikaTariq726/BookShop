
# 📚 FAST-NU Book Shop – MERN Stack Project

This is a simple Book Shop Management App built as my **first MERN Stack project**. It features authentication, role-based access, and CRUD operations for books and students.

---

## 🚀 Tech Stack

- **Frontend:** React + Vite
- **Backend:** Node.js + Express
- **Database:** MongoDB (with MongoDB Compass for local visualization)
- **Authentication:** JWT, bcrypt
- **Token Handling:** Automatic logout on token failure

---

## 🧠 Features

- 🔒 Secure Login/Signup using JWT and bcrypt
- 📚 Manage Books (Add/View)
- 🎓 Manage Students (Add/View)
- 🧼 Auto Logout on invalid or expired token
- 🧭 Protected Routes using JWT
- 🧩 Models for Books and Students

---

## 📸 Screenshots

*(Add your screenshots here)*

---

## 🛠️ Setup Instructions

### 📁 1. Clone the Repository

```bash
git clone https://github.com/your-username/bookshop-app.git
cd bookshop-app
````

### 📦 2. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

### ⚙️ 3. Environment Variables

Create a `.env` file in the **backend** directory with the following content:

```env
PORT=3001
JWT_SECRET=your_jwt_secret
URL=your_mongodb_connection_string
```

---

## ▶️ Running the Project

### ✅ Start Backend

```bash
cd server
npx nodemon index.js
```

### ✅ Start Frontend

```bash
cd client
npm run dev
```

---

## 🧪 Tools Used

* 🔐 `bcrypt` – for password hashing
* 🪙 `jsonwebtoken` – for secure token-based authentication
* 📡 `axios` – for HTTP requests
* 🧭 `MongoDB Compass` – for local database inspection

---

## 🙌 Acknowledgments

This project was created to learn and practice the MERN stack from scratch. Huge thanks to open-source tutorials and docs that helped along the way.

---

## 📌 Notes

* Ensure MongoDB is running locally or provide a correct MongoDB Atlas URL.
* This app currently supports basic role-free access — ideal for students learning authentication and API integration.

---
