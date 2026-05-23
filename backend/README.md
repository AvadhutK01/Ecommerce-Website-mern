# ⚙️ E-Commerce Backend (API)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

This directory contains the core API engine for the E-Commerce platform. It handles everything from user authentication and payment processing to product management and order fulfillment.

---

## 🛠️ Tech Stack

- **Server Framework**: [Express.js](https://expressjs.com/)
- **Runtime Environment**: [Node.js](https://nodejs.org/)
- **Database**: [MongoDB](https://www.mongodb.com/) with [Mongoose ODM](https://mongoosejs.com/)
- **Authentication**: [JSON Web Tokens (JWT)](https://jwt.io/) & [Bcryptjs](https://www.npmjs.com/package/bcryptjs)
- **Payment Gateway**: [Razorpay](https://razorpay.com/)
- **Cloud Storage**: [Cloudinary](https://cloudinary.com/) (Product & User images)
- **Mailing Service**: [Nodemailer](https://nodemailer.com/)

---

## 📂 Core Structure

```bash
📂 backend
├── 📂 config         # DB connection & Environment config
├── 📂 controllers    # Business logic for all routes
├── 📂 middlewares    # Auth, Error handling, Multer
├── 📂 models         # MongoDB Schemas (User, Product, Order)
├── 📂 routes         # API endpoint definitions
├── 📂 util           # Helper functions & SendMail logic
├── 📄 app.js         # App configuration
└── 📄 server.js      # Server entry point
```

---

## 🛰️ API Endpoints Summary

### User Routes (`/api/v1`)
- `POST /register`: Register a new user
- `POST /login`: Login user
- `GET /me`: Get current user profile
- `PUT /password/update`: Update password

### Product Routes (`/api/v1`)
- `GET /products`: Fetch all products (with filters)
- `GET /product/:id`: Get product details
- `POST /admin/product/new`: Create new product (Admin)

### Order Routes (`/api/v1`)
- `POST /order/new`: Create a new order
- `GET /order/:id`: Get order details
- `GET /orders/me`: Get current user's orders

---

## 🛠️ Setup & Running

1. **Install dependencies**:
   ```bash
   npm install
   ```
2. **Setup environment variables**:
   Create a `.env` file in the `backend` folder:
   ```env
   PORT=4000
   DB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_NAME=your_cloudinary_name
   RAZORPAY_KEY_ID=your_razorpay_key
   ```
3. **Start the server**:
   ```bash
   npm start # Uses nodemon for development
   ```

---
Built with ⚙️ for reliability.
