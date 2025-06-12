# 🏢 Visitor Management System – Backend (MERN)

This is the **backend** of a multi-tenant SaaS Visitor Management System built with **Node.js**, **Express.js**, **MongoDB**, and **JWT** for authentication. It supports multiple companies, role-based access (admin/receptionist), and includes a seed script to create a default admin.

---

## 🚀 Features

- 🔐 JWT-based authentication
- 🏢 Multi-company login system
- 🧑‍💼 Role-based access: Admin & Receptionist
- 🌱 `seed.js` script to create default company/admin
- 📧 Email notification support (via Nodemailer)

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Nodemailer

---

## 🔧 Environment Setup

Create a `.env` file in the `backend/` root:

```env
MONGO_URI=your_mongo_url
JWT_SECRET=your_secret_key
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
PORT=5000
```

---
🌱 Seeding Admin
Run this to insert a default company + admin into the database:

node seed.js
Ensure your MongoDB connection string is correct.


▶️ Running Backend

npm install
npm run start
Server will run on port 5000 (or as per your .env).

🔗 Frontend
👉 https://github.com/Arya4546/vms_frontend
