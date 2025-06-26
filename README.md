# Red Hibiscus

This is the frontend of **EatsC**, a full-stack food ordering platform where customers can explore restaurant menus, place orders, and track them live. Restaurants can register, upload menu items, and manage incoming orders. Built with **React**, the frontend interacts with a **Node.js**, **Express**, and **MongoDB** backend.

---

## Live Site

**URL:** [https://eatsc-frontendrs.onrender.com](https://eatsc-frontendrs.onrender.com)

![Landing Page](https://github.com/user-attachments/assets/6456c0c7-1952-4f3b-83d7-cae0aa0fc5f2)

---

## User Roles

### Customers
- Register and log in using Auth0
- Browse restaurant menus and add dishes to cart
- Place orders and pay using Stripe
- View real-time order status updates

### Restaurants
- Register and log in as a restaurant
- Add, update, or remove their own food items
- View and manage customer orders and statuses

---

## Core Features

### Homepage
- Loads food menu items from MongoDB via backend APIs
- Items include image, name, price, and add-to-cart functionality
- Clicking on a dish shows detailed view and options

### Cart System
- Users can manage their cart globally using React Context API
- Quantity updates, item removal, and dynamic price calculation supported

### Authentication
- Role-based access powered by Auth0
- Session persistence for both customer and restaurant accounts

### Checkout and Payments
- Stripe is integrated for test-mode payment processing
- Successful payment redirects to an order confirmation screen

### Live Order Tracking
- Order status is fetched from MongoDB and updated in real time
- Stages include: Order Placed, Preparing, Out for Delivery
- Provides customers with transparency after checkout

---

## Technology Stack

- **Frontend**: React, Tailwind CSS, React Router
- **Authentication**: Auth0
- **State Management**: React Context API
- **Payments**: Stripe
- **Media Storage**: Cloudinary (via backend API)
- **Backend**: Node.js, Express
- **Database**: MongoDB

---

## Highlights

- Fully responsive interface optimized for mobile and desktop
- Clean navigation flow with quick transitions
- Support for two distinct user types (customers and restaurants)
- Real-time tracking of orders using backend updates
- Modular code structure for maintainability and scalability

---

## Project Objectives

This project demonstrates the ability to:

- Build a scalable and interactive frontend in React
- Integrate secure authentication and payments into a live app
- Handle role-based access control on the frontend
- Consume RESTful APIs and dynamically render data
- Design a real-world ordering system with live status updates

---

## License

This project is intended for demonstration and educational purposes only.
