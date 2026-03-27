# 🛒 FOREVER E-commerce App

A full-stack **MERN-based E-commerce web application** with secure authentication, product management, cart system, and integrated payment gateway.

---

## 📌 Features

### 👤 User Features
- User Registration & Login (JWT Authentication)
- Browse Products
- Add to Cart
- Update Quantity / Remove Items
- Secure Checkout
- Order Placement

### 🛠️ Admin Features
- Add / Update / Delete Products
- Manage Orders
- Dashboard Overview

### 💳 Payment Integration
- Integrated with Stripe for secure payments

---

## 🧱 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)

### Authentication
- JWT (JSON Web Tokens)
- bcrypt.js

### Tools & Platforms
- GitHub
- Postman
- VS Code

---

## 📁 Project Structure

FOREVER-E-commerce-App/
│
├── frontend/          # React frontend
│   ├── src/
│   ├── public/
│
├── backend/           # Node + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── config/
│
├── .gitignore
├── README.md

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

git clone https://github.com/BuildWithAditi/FOREVER-E-commerce-App.git  
cd FOREVER-E-commerce-App

---

### 2️⃣ Setup Backend

cd backend  
npm install  

Create `.env` file:

PORT=8000  
MONGO_URI=your_mongodb_connection  
JWT_SECRET=your_secret_key  
STRIPE_SECRET_KEY=your_stripe_secret  

Run backend:

npm run dev

---

### 3️⃣ Setup Frontend

cd frontend  
npm install  
npm run dev  

---

## 🔐 Environment Variables

Create a `.env` file in the backend:

| Variable | Description |
|----------|------------|
| PORT | Server Port |
| MONGO_URI | MongoDB Connection String |
| JWT_SECRET | JWT Secret Key |
| STRIPE_SECRET_KEY | Stripe API Key |

---

## 🛡️ Security Best Practices

- `.env` is ignored via `.gitignore`
- Sensitive keys are not exposed
- Token-based authentication implemented
- Passwords are hashed using bcrypt

---

## 🧪 API Endpoints (Sample)

### Auth
- POST /api/v1/user/register  
- POST /api/v1/user/login  

### Products
- GET /api/v1/product/all  
- POST /api/v1/product/create  

### Orders
- POST /api/v1/order/create  
- GET /api/v1/order/user  

---

## 📦 Deployment

You can deploy using:
- Frontend → Vercel / Netlify  
- Backend → Render / Railway  

---

## 👩‍💻 Author

**Aditi Parmar**  
CSE (AI & ML) Student | MERN Developer  

---


## 💡 Future Improvements

- Wishlist feature  
- Product reviews & ratings  
- Admin analytics dashboard  
- Order tracking system  

---

🔥 Built with passion and real-world development practices
