
# 🛍️ MERN E-Commerce Project

![MERN Stack](https://img.shields.io/badge/Stack-MongoDB%20%7C%20Express%20%7C%20React%20%7C%20Node.js-green)

A **MERN-based E-commerce web application** developed as part of our **Industrial Training Project**.  
The project provides a complete shopping experience for customers along with an admin dashboard for management.

---

## 🚀 Features

### Customer Side
- User registration and login
- Browse and search products
- Add products to cart
- Place orders and checkout

### Admin Side
- Admin login
- Manage products (add, edit, delete)
- View customer orders
- Manage users

---

## 🛠️ Tech Stack
- **Frontend** → React.js  
- **Backend** → Node.js + Express.js  
- **Database** → MongoDB  

---

## 📂 Project Structure

```
Mern-Ecommerce-master/
│── frontend/        # Customer-facing React app
│── backend/         # Node.js + Express API
│── admin/           # Admin Dashboard (React)
```

---

## ⚡ Installation & Setup

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [NPM](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/MenathNDGD/MERN-Ecommerce.git
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

<details>
<summary><code>/admin/.env</code></summary>

```env
VITE_BACKEND_URL = "http://localhost:4000"
```

</details>

<details>
<summary><code>/backend/.env</code></summary>

```env
MONGODB_URI =

CLOUDINARY_API_KEY =

CLOUDINARY_SECRET_KEY =

CLOUDINARY_CLOUD_NAME =

JWT_SECRET =

ADMIN_EMAIL = "admin@trendify.com" #For testing only

ADMIN_PASSWORD = "admin@123" #For testing only

```

</details>

<details>
<summary><code>/frontend/.env</code></summary>

```env
VITE_BACKEND_URL = "http://localhost:4000"
```

</details>

Replace the placeholder values with your actual Appwrite credentials. add this

1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/Mern-Ecommerce.git
cd Mern-Ecommerce-master
```

2️⃣ Install Dependencies  
```bash
cd backend
npm install
npm start
```

```bash
cd frontend
npm install
npm run dev
```

```bash
cd admin
npm install
npm run dev
```

---

## 👨‍💻 Team Members

- **Shreya Das** – Brainware University  
- **Krishan Mohan Singh** – Brainware University  
- **Anirban Mondal** – Brainware University  
- **Riya Kumari** – CEMK  
- **Arzoo Aftab** – BBIT

---


