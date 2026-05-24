# E-Commerce Web Application

A full-stack e-commerce web application that allows users to browse products, add items to the cart, place orders, and manage purchases efficiently. The application includes user authentication, role-based access, product management, and order tracking functionalities.

---

## Features

- User Authentication & Authorization
- Role-Based Access Control (Admin/User)
- Product Catalog Management
- Add to Cart Functionality
- Checkout & Order Placement
- Order Tracking System
- Backend REST APIs
- Responsive Design for Mobile & Desktop
- Database Integration

---

## Tech Stack

### Frontend
- React.js
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
Choose any one:
- MongoDB
- MySQL
- PostgreSQL

### Authentication
- JWT (JSON Web Token)
- bcrypt.js

---

## Project Structure

```bash
ecommerce-web-app/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── README.md
└── package.json
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/ecommerce-web-app.git
```

### Navigate to Project Directory

```bash
cd ecommerce-web-app
```

---

## Backend Setup

```bash
cd server
npm install
```

### Create `.env` File

```env
PORT=5000
DB_URI=your_database_connection
JWT_SECRET=your_secret_key
```

### Run Backend

```bash
npm start
```

---

## Frontend Setup

```bash
cd client
npm install
npm start
```

---

## API Endpoints

### Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register User |
| POST | `/api/auth/login` | Login User |

### Products

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/products` | Get All Products |
| POST | `/api/products` | Add Product (Admin) |
| PUT | `/api/products/:id` | Update Product |
| DELETE | `/api/products/:id` | Delete Product |

### Orders

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/orders` | Place Order |
| GET | `/api/orders` | Get User Orders |
| GET | `/api/orders/:id` | Get Order Details |

---

## User Roles

### Admin
- Manage Products
- Update Inventory
- View Orders
- Manage Users

### User
- Browse Products
- Add Products to Cart
- Place Orders
- Track Orders

---

## Core Functionalities

- Product Listing Page
- Product Details Page
- Shopping Cart
- Secure Checkout
- Order History
- Authentication System

---

## Responsive Design

The application is optimized for:

- Desktop Devices
- Tablets
- Mobile Phones

---

## Learning Outcomes

Through this project, you will learn:

- Full-Stack Web Development
- REST API Development
- Database Management
- Authentication & Authorization
- Role-Based Access Control
- State Management
- Frontend-Backend Integration
- Dynamic Data Handling
- Real-World E-Commerce Workflow

---

## Future Enhancements

- Online Payment Gateway Integration
- Product Reviews & Ratings
- Wishlist Functionality
- Email Notifications
- Admin Dashboard Analytics
- Search & Filter Products
- Coupon & Discount System

---

## Author

Bhavani H

---

## License

This project is licensed under the MIT License.
