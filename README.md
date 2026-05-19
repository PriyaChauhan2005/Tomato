# Food Delivery App (MERN Stack)

A full-stack food delivery web application built using the MERN stack (MongoDB, Express, React, Node.js). The application includes a customer-facing frontend, an admin dashboard for management, and a robust backend API.

## 🚀 Features

### Customer Frontend
- Browse a menu of delicious food items.
- Filter foods by category.
- Add/Remove items from the cart.
- Secure checkout and payment processing using Stripe.
- View order history and track order status.
- User authentication (Login/Signup).

### Admin Dashboard
- View and manage all user orders.
- Update order statuses (e.g., Food Processing, Out for Delivery, Delivered).
- Add new food items to the menu with image upload.
- View and remove existing food items.

### Backend API
- RESTful APIs for Users, Food, Cart, and Orders.
- Secure password hashing and JWT-based authentication.
- Integration with Stripe for payment processing.
- MongoDB for robust data storage.

## 💻 Tech Stack

- **Frontend:** React.js, Vite, React Router, Context API, Axios, CSS
- **Admin Panel:** React.js, Vite, React Router, Axios, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Payment Gateway:** Stripe
- **Authentication:** JSON Web Tokens (JWT) & bcrypt

## 🛠️ Installation and Setup

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed on your machine.

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd Food-del
```

### 2. Backend Setup
```bash
cd backend
npm install
```
Create a `.env` file in the `backend` directory and add the following variables:
```env
PORT=4000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
```
Start the backend server:
```bash
npm run server
```

### 3. Frontend Setup
```bash
cd frontend
npm install
```
Start the frontend development server:
```bash
npm run dev
```

### 4. Admin Panel Setup
```bash
cd admin
npm install
```
Start the admin development server:
```bash
npm run dev
```

## 🌐 Running the App
- **Frontend:** Open `http://localhost:5173` (or the port shown in your terminal)
- **Admin Panel:** Open `http://localhost:5174`
- **Backend API:** Runs on `http://localhost:4000`

## 📁 Folder Structure
- `/frontend`: Customer-facing React application.
- `/admin`: React application for restaurant administrators.
- `/backend`: Node.js/Express REST API and MongoDB configuration.



