# EatsC – Frontend

This is the frontend of **EatSC**, a full-stack food ordering platform that provides users with an intuitive interface to explore restaurant menus, manage their orders, and complete secure transactions. It is built using **React** and connects to a backend powered by **Node.js**, **Express**, and **MongoDB**.

---

## Live Site

**URL:** [https://eatsc-frontendrs.onrender.com](https://eatsc-frontendrs.onrender.com)

![Domo_image](https://github.com/user-attachments/assets/b88f3fcd-2752-4024-b877-87b57f54c89f)
---

###  Homepage

- Fetches dish listings from MongoDB via backend APIs.
- Each dish displays a name, price, image, and an “Add to Cart” option.
- Clicking a dish reveals detailed information and quantity selection.

###  Cart System

- Cart is managed globally using React Context API.
- Users can add or remove items and adjust quantities.
- The cart summary dynamically calculates subtotals and total cost.

###  User Authentication

- Integrated with Auth0 for secure login and logout.
- Authenticated users have a persistent session and access to checkout.

###  Checkout & Payments

- Users can proceed to checkout after logging in.
- Stripe is integrated for secure payment handling.
- After payment, users are redirected to an order success screen.

###  Live Order Tracking

- After placing an order, users can **view the real-time status** of their order.
- Status updates (e.g., "Order Placed", "Preparing", "Out for Delivery") are dynamically shown.
- Data is fetched from MongoDB, which stores order metadata and status updates.

---

##  Architecture

- **Frontend**: React, Tailwind CSS, React Router, Axios
- **State Management**: React Context API for cart and auth state
- **Authentication**: Auth0
- **Payments**: Stripe
- **Media**: Cloudinary (handled via backend)
- **Backend**: Node.js + Express
- **Database**: MongoDB (orders, dishes, and user metadata)

---

##  Highlights

- Modern, responsive UI
- Clean navigation and fast loading experience
- Seamless user flow: browse → cart → authenticate → checkout → track order
- Realtime feedback on order lifecycle
- Backend interaction designed for scalability and separation of concerns

---

##  Main Asspects

This project showcases:

- Proficiency in building production-ready React applications
- Integration of third-party services like Auth0, Stripe, and Cloudinary
- RESTful API consumption and async data handling
- Real-time order tracking using persistent data from MongoDB
- Clean component structure and maintainable frontend architecture

---

## License

This project is intended for demonstration and educational purposes.

