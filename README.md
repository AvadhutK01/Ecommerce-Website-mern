# 🛒 MERN Stack E-Commerce Platform

![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue.svg?style=for-the-badge)
![License](https://img.shields.io/badge/license-ISC-green.svg?style=for-the-badge)
![Website Status](https://img.shields.io/badge/Status-Development-orange.svg?style=for-the-badge)

Welcome to the **Complete E-Commerce Solution**! This project is a feature-rich, full-stack web application built using the MERN power stack (MongoDB, Express, React, Node.js). It provides a seamless shopping experience with integrated payments, user authentication, and a robust admin dashboard.

---

## 🌟 Key Features

- **🛍️ Product Management**: Detailed product listings, searching, and advanced filtering.
- **🔐 Secure Authentication**: JWT-based login/signup with role-based access control (Admin/User).
- **💳 Payment Integration**: Secure transactions powered by **Razorpay**.
- **📦 Order Tracking**: Real-time order management and history.
- **☁️ Cloud Storage**: Image management via **Cloudinary**.
- **📧 Notifications**: Automated email notifications for orders and account actions.

---

## 🏗️ Project Structure

```bash
.
├── 📂 backend         # Node.js & Express API
│   ├── 📂 config      # Database and Config files
│   ├── 📂 controllers # Request Handlers
│   ├── 📂 models      # Mongoose Schema Definitions
│   └── 📂 routes      # API Endpoints
├── 📂 frontend        # React Frontend
│   ├── 📂 src/actions # Redux Actions
│   ├── 📂 src/comp    # React Components (UI)
│   └── 📂 src/reducers # Redux State Management
└── 📄 package.json    # Root Scripts for Concurrency
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+)
- MongoDB Atlas account or local installation
- Cloudinary Account
- Razorpay API Keys

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AvadhutK01/Ecommerce-Website-mern.git
   cd Ecommerce-Website-mern
   ```

2. **Install Dependencies**
   ```bash
   # Install root, backend, and frontend dependencies
   npm install
   cd backend && npm install
   cd ../frontend && npm install
   ```

3. **Environment Variables**
   Create `.env` files in both `backend` and `frontend` directories using the provided templates (if applicable).

4. **Run the Application**
   From the root directory, start both the client and server concurrently:
   ```bash
   npm start
   ```
   - Frontend runs on: `http://localhost:3000`
   - Backend runs on: `http://localhost:4000`

---

## 🛠️ Tech Stack

| Frontend | Backend | Tools |
| :-- | :-- | :-- |
| React | Node.js | Mongoose |
| Redux | Express | Cloudinary |
| Material UI | MongoDB | Razorpay |

---

## 📄 License
Distributed under the ISC License. See `LICENSE` for more information.

---
Built with ❤️ by AvadhutK01(https://github.com/AvadhutK01)
