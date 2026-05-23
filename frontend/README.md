# ecommerce-mern-frontend
# 💻 E-Commerce Frontend (UI)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![Material UI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)

This is the interactive frontend of the E-Commerce platform. Designed for speed, responsiveness, and a premium user experience, it leverages modern React patterns and robust state management.

---

## 🎨 Design & UI

- **Framework**: [Material UI (MUI)](https://mui.com/) for sleek, modern components.
- **Styling**: Vanilla CSS & MUI-styled components for a pixel-perfect layout.
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/) and MUI Icons.
- **Carousel**: [React Material UI Carousel](https://www.npmjs.com/package/react-material-ui-carousel) for stunning hero sections.

---

## 🧠 State Management (Redux)

The application uses **Redux** with **Thunk** middleware to manage global state smoothly:
- **Products**: List, details, and reviews.
- **User**: Profile, login status, and permissions.
- **Cart**: Persistent cart items using `redux-persist`.
- **Orders**: Creation and history management.

---

## 📂 Project Structure

```bash
📂 frontend/src
├── 📂 actions       # Redux action creators (Async logic)
├── 📂 component     # Reusable UI components
│   ├── 📂 Layout    # Navbar, Footer
│   ├── 📂 Route     # Protected & Public routes
│   └── 📂 Product   # Product Cards, Details
├── 📂 constants     # Redux action type constants
├── 📂 reducers      # Redux reducer logic
└── 📄 store.js      # Centralized Redux store config
```

---

## 🚀 Setup & Running

1. **Install dependencies**:
   ```bash
   npm install
   ```
2. **Start the development server**:
   ```bash
   npm start
   ```
3. **Build for production**:
   ```bash
   npm run build
   ```

---

## ✨ Key UI Components

- **Navigation**: Dynamic navbar with sticky behavior.
- **Product Grid**: Responsive grid with search and category filtering.
- **Admin Dashboard**: Comprehensive panel for managing products, orders, and users.
- **Payment Flow**: Seamless integration with Razorpay popup.

---
Crafted with ✨ for a stunning experience.
