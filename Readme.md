# 🚴 Bike Rental System

## 📌 Project Overview
The **Bike Rental System** is a **full-stack web application** designed to facilitate the seamless rental of bikes. Built using **FastAPI, MongoDB, HTML, CSS, and JavaScript**, this platform enables users to register, book bikes, make payments, and track real-time availability.

## 🎯 Features
- **User Authentication** (Signup/Login with JWT authentication)
- **Real-time Bike Availability Tracking**
- **Bike Booking & Rental Management**
- **Payment Integration** (Stripe/PayPal)
- **Admin Panel** for managing rentals and users
- **Responsive & Intuitive UI**

## 🛠️ Tech Stack
### **Frontend:**
- HTML, CSS, JavaScript
- Bootstrap/Tailwind CSS (for styling)
- Fetch API (for handling API requests)

### **Backend:**
- FastAPI (Python framework)
- MongoDB (NoSQL database for storing user and rental data)
- JWT Authentication (User authentication & security)

### **Payment Integration:**
- Stripe or PayPal API

## 📂 Project Structure
```
📦 bike-rental-system
├── 📂 frontend
│   ├── index.html
│   ├── styles.css
│   ├── app.js
│   ├── login.html
│   ├── booking.html
│   ├── payment.html
│
├── 📂 backend
│   ├── main.py  # FastAPI main application
│   ├── models.py  # Database models
│   ├── routes.py  # API routes
│   ├── database.py  # MongoDB connection
│   ├── auth.py  # JWT authentication
│
├── requirements.txt
├── README.md
```

## 🚀 Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/bike-rental-system.git
cd bike-rental-system
```

### **2️⃣ Set Up the Backend**
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### **3️⃣ Set Up the Frontend**
Simply open `index.html` in your browser, or use a local server:
```bash
cd frontend
python -m http.server 8000
```

## 📡 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/signup` | Register a new user |
| POST | `/auth/login` | Authenticate user & get token |
| GET | `/bikes/available` | Get available bikes |
| POST | `/bikes/book` | Book a bike |
| POST | `/payment/process` | Process payment |

## 🏗️ Future Enhancements
- Add **Google OAuth** for authentication
- Implement **Review & Rating System**
- Introduce **Mobile App Integration**

## 🤝 Contribution
Feel free to **fork, raise issues, or contribute** to this project!

## 📜 License
This project is licensed under the **MIT License**.

---
### 🎉 Happy Coding! 🚀
