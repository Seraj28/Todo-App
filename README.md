# 📌 MERN Stack ToDo App  

A full-stack **ToDo Application** built with the **MERN stack** that demonstrates user authentication (Login/Signup) and complete CRUD operations (Create, Read, Update, Delete).  

The app features a clean UI with **React + TailwindCSS** and a secure backend powered by **Express.js, JWT Authentication, Middleware, and MongoDB Atlas**.  

---

## 🚀 Features  

### 🔐 Authentication  
- User **Signup & Login** with JWT-based authentication.  
- Protected routes for authorized users only.  

### ✅ ToDo Management  
- Add new tasks.  
- Update existing tasks.  
- Mark tasks as completed (checkout).  
- Delete tasks.  

### 🎨 Modern UI  
- Built with **React.js** & styled using **TailwindCSS**.  
- Responsive and clean design.  

### 🛠 Robust Backend  
- Structured with **Controllers, Routes, Models, Middleware**.  
- Secure API endpoints tested with **Postman**.  

### 🌍 Database  
- Fully managed with **MongoDB Atlas**.  

---

## 📂 Project Structure  

### 🔹 Backend (`/backend`)  

backend/
│── controllers/ # Business logic (ToDo, Auth, etc.)
│── middleware/ # Auth middleware (JWT)
│── models/ # Mongoose schemas
│── routes/ # API endpoints
│── .env # Environment variables (Mongo URI, JWT secret)
│── server.js # Express app entry point


### 🔹 Frontend (`/frontend`)  

frontend/
│── src/
│ ├── components/ # Reusable React components
│ ├── assets/ # Static assets (icons, images, etc.)
│ └── App.js # Main React app
│── public/ # Static files
│── tailwind.config.js # TailwindCSS config


---

## ⚙️ Tech Stack  

- **Frontend:** React.js, TailwindCSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas (Mongoose ODM)  
- **Authentication:** JWT (JSON Web Tokens)  
- **API Testing:** Postman  
- **Version Control:** Git & GitHub  

---

## 🖥️ Installation & Setup  

### 1️⃣ Clone the repo  
```bash
git clone https://github.com/<your-username>/<your-repo>.git
2️⃣ Setup Backend
cd backend
npm install
Create a .env file inside backend/ and add:
PORT=5000
MONGO_URI=your-mongodb-atlas-uri
JWT_SECRET=your-secret-key
Run the backend:
npm start
3️⃣ Setup Frontend
cd frontend
npm install
npm start
🌐 Live Demo

🔗 Live Project Link

🧑‍💻 Author

Md Seraj

💼 Aspiring MERN Stack Developer

📧 [Your Email]

🌐 [Your LinkedIn]

✨ This project highlights my MERN stack skills with real-world practices like JWT authentication, middleware, environment variables, and MongoDB Atlas. Perfect for scalable, production-ready applications.
