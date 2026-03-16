# 🐾 PETHUB – Pet Care Platform

Node.js • Express • React • MongoDB

A comprehensive platform for pet care services and consultation 🐶🐱  
Empowering pet owners to book appointments, manage pets, access expert advice, and use modern online services with ease.

---

## 🎯 Overview

PETHUB is a full-stack web application designed to connect pet owners with veterinary clinics and pet care services. The platform provides:

- 🗓️ **Appointment Booking** – Schedule visits with veterinarians and service providers
- 👩‍⚕️ **Doctor & Staff Management** – Admin panel for managing doctors, staff, and schedules
- 🐕 **Pet Profiles** – Store and manage pet information, medical history, and vaccination records
- 💬 **Consultation & News** – Access expert advice, articles, and the latest pet care news
- 💳 **Online Payment** – Secure payment integration (MoMo, PayPal, VNPay)
- 📊 **Admin Dashboard** – Analytics, customer management, and service control

---

## ✨ Features

### 👤 User Authentication

- Secure registration & login (JWT)
- Role-based access (admin, doctor, customer)
- Session management

### 🗓️ Booking System

- Real-time appointment scheduling
- Booking management for users and admins
- Email/SMS notifications (optional)

### 🐾 Pet & Customer Management

- Add, edit, and view pet profiles
- Customer information management
- Medical and service history tracking

### 🏥 Service & Doctor Management

- CRUD for services, categories, and doctors
- Doctor schedules and availability
- Service pricing and descriptions

### 📰 News & Blog

- Post and manage news articles
- Display latest updates to users

### 💳 Payment Integration

- MoMo, PayPal, VNPay support
- Transaction history and status tracking

### 🛡️ Security

- Token-based authentication
- Input validation & error handling
- Secure file upload for pet images

---

## 🛠️ Tech Stack

**Frontend:**

- ReactJS (Create React App)
- React Router, Context API
- Axios, CSS Modules

**Backend:**

- Node.js, Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Multer (file upload)
- RESTful API

**Other:**

- MoMo, PayPal, VNPay SDKs
- Cloud/Local image storage

---

## 📁 Project Structure

```
PETHUB/
├── client/           # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── ...
│   └── public/
├── server/           # Node.js backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── ...
├── ADMIN_CODE_GUIDE.md
└── README.md
```

---

## 🚀 Installation & Setup

**Prerequisites:**

- Node.js (v16+), npm
- MongoDB
- (Optional) MoMo/PayPal/VNPay developer accounts

**Steps:**

1. Clone the repository:

   ```
   git clone https://github.com/MyDang2705/PETHUB.git
   cd PETHUB
   ```

2. Install backend dependencies:

   ```
   cd server
   npm install
   ```

3. Install frontend dependencies:

   ```
   cd ../client
   npm install
   ```

4. Configure environment variables:
   - Create `.env` files in both `server/` and `client/` as needed (see sample `.env.example`).

5. Start the backend server:

   ```
   cd ../server
   npm start
   ```

6. Start the frontend:
   ```
   cd ../client
   npm start
   ```

---

## 🏗️ Architecture

- **Frontend:** Component-based React SPA, API-driven, protected routes for admin
- **Backend:** RESTful API, MVC pattern, JWT authentication, role-based access
- **Database:** MongoDB for all persistent data

---

## 🔌 API Endpoints

- `/api/auth` – Authentication (login, register)
- `/api/bookings` – Booking management
- `/api/customers` – Customer & pet management
- `/api/doctors` – Doctor management
- `/api/services` – Service management
- `/api/news` – News/blog
- `/api/payments` – Payment processing

---

## 📝 Development

- **Run tests:**
  - Backend: `npm test` (in server/)
  - Frontend: `npm test` (in client/)

- **Lint & format:**
  - Use ESLint and Prettier configs provided

- **Git workflow:**
  - Feature branches, pull requests, code review

---

## 📄 License

MIT License – feel free to use and contribute!

---

Made with ❤️ for pet lovers and clinics.
