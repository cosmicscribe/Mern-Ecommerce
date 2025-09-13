
# 🛍️ MERN E-Commerce Project

A full-stack **E-commerce web application** built using the **MERN stack (MongoDB, Express.js, React, Node.js)**.  
This project includes a **customer-facing store**, a **backend REST API**, and an **admin dashboard** for managing products, orders, and users.

---

## 🚀 Features

### Customer Frontend
- User authentication (login/signup with JWT)
- Product browsing and searching
- Shopping cart functionality
- Order placement and checkout

### Admin Dashboard
- Secure admin login
- Manage products (add, edit, delete)
- View and process orders
- Manage users

### Backend (API)
- RESTful API using Express.js
- MongoDB for data storage
- Cloudinary for image upload
- JWT authentication and authorization
- Middleware for security and request handling

---

## 🛠️ Tech Stack

**Frontend (User & Admin)**
- React.js (Vite for admin, CRA/Vite for frontend)
- Tailwind CSS
- Axios

**Backend**
- Node.js
- Express.js
- MongoDB + Mongoose
- Cloudinary
- JWT Authentication

---

## 📂 Project Structure

```
Mern-Ecommerce-master/
│── e-commerce/
│   ├── frontend/        # Customer-facing React app
│   ├── backend/         # Node.js + Express API
│   ├── admin/           # Admin Dashboard (React + Tailwind + Vite)
│   └── ...
```

---

## ⚡ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Mern-Ecommerce.git
cd Mern-Ecommerce-master/e-commerce
```

### 2️⃣ Backend Setup
```bash
cd backend
npm install
```
Create a `.env` file in `/backend` with the following:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```
Run backend server:
```bash
npm start
```

### 3️⃣ Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### 4️⃣ Admin Dashboard Setup
```bash
cd admin
npm install
npm run dev
```

---

## 🌍 Deployment

- **Frontend & Admin** → Vercel / Netlify  
- **Backend** → Render / Vercel / Railway / Heroku  
- **Database** → MongoDB Atlas  

---

## 👨‍💻 Team Members

- **Shreya Das** – Brainware University  
- **Krishan Mohan Singh** – Brainware University  
- **Anirban Mondal** – Brainware University  
- **Riya Kumari** – CEMK  
- **Arzoo Aftab** – BBIT  

---

## 📚 References & Resources

- [GeeksforGeeks (GFG)](https://www.geeksforgeeks.org/)  
- [YouTube Tutorials](https://www.youtube.com/)  
- [Cloudinary Documentation](https://cloudinary.com/documentation)  
- [OpenAI / ChatGPT](https://openai.com/chatgpt)  

---

## 📸 Screenshots

### 🖥️ Admin Panel

#### View Orders
<img width="1897" height="867" alt="Image" src="https://github.com/user-attachments/assets/6ca51ca7-87b0-4f64-94da-80e634c6d52e" />
#### List Items
<img width="1896" height="866" alt="Image" src="https://github.com/user-attachments/assets/40f01dd3-83f4-47d0-aa1b-06aaee3deb15" />
#### Add Items
<img width="1893" height="867" alt="Image" src="https://github.com/user-attachments/assets/5c1002df-6112-403c-8cca-fbe10d55af0c" />


---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License
This project is licensed under the MIT License.
