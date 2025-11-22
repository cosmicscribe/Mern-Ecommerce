🛍️ MERN E-Commerce Project

A full-stack MERN E-Commerce application developed as part of our Industrial Training Project.
It includes a complete customer shopping experience and a powerful admin dashboard for product & order management.

🔗 Live Project Links
Platform	Link
🛒 Store (Frontend)	https://mern-ecommerce-7t6x.vercel.app/

🔐 Admin Dashboard	https://trendify-admin-zeta.vercel.app/
🔐 Admin Demo Credentials
Email: admin@gmail.com
Password: admin123

🚀 Features
🧑‍💻 Customer Side

User Authentication (Register/Login)

Browse & Search Products

Add to Cart

Place Orders & Checkout

🛠️ Admin Side

Admin Login

Add, Edit, Delete Products

View & Manage Customer Orders

Manage Users

🛠️ Tech Stack

Frontend → React.js (Vite)

Backend → Node.js + Express.js

Database → MongoDB

Media Storage → Cloudinary

📂 Project Structure
Mern-Ecommerce-master/
│── frontend/         # Customer-facing React app
│── backend/          # Node.js + Express API
│── admin/            # Admin Dashboard (React)

⚡ Installation & Setup Guide

Follow the steps below to run the project locally.

1️⃣ Clone the Repository
git clone https://github.com/your-username/Mern-Ecommerce.git
cd Mern-Ecommerce-master

2️⃣ Backend Setup
cd backend
npm install
npm start

3️⃣ Frontend Setup (Store)
cd frontend
npm install
npm run dev

4️⃣ Admin Panel Setup
cd admin
npm install
npm run dev

🔑 Environment Variables

Create .env files in each folder as shown below:

📌 /admin/.env
VITE_BACKEND_URL="http://localhost:4000"

📌 /backend/.env
MONGODB_URI=

CLOUDINARY_API_KEY=
CLOUDINARY_SECRET_KEY=
CLOUDINARY_CLOUD_NAME=

JWT_SECRET=

ADMIN_EMAIL="admin@trendify.com"
ADMIN_PASSWORD="admin@123"

📌 /frontend/.env
VITE_BACKEND_URL="http://localhost:4000"


⚠️ Replace placeholder values with your actual MongoDB, Cloudinary, and JWT credentials.

👨‍💻 Team Members

Shreya Das – Brainware University

Krishan Mohan Singh – Brainware University

Anirban Mondal – Brainware University

Riya Kumari – CEMK

Arzoo Aftab – BBIT
