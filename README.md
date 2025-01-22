This is a full-stack food ordering website built using **React.js**, **Node.js**, **Express.js**, **MongoDB**, and **Stripe**. The project includes a frontend website, an admin panel, and a backend server, providing a seamless user experience for food ordering and payment.

## Features

### Frontend
- **User Authentication**: Account creation and login functionality.
- **Shopping Cart**: Add, update, or remove items in the cart.
- **Food Ordering**: Browse food items and place orders.
- **Stripe Payment Integration**: Secure online payment for orders.

### Backend
- **Admin Panel**: Manage food items, orders, and users.
- **Order Management**: Track and update order statuses.
- **Database**: MongoDB is used to store user, food, and order details.
- **Secure API**: Built using Express.js and Node.js.

## Installation

Follow these steps to set up the project locally:

### Prerequisites
- Node.js installed on your machine.
- MongoDB server running locally or on the cloud.
- Stripe account for payment gateway integration.

### Clone the Repository
```bash
git clone https://github.com/sithumimadhushika/food-delivery-website.git
cd food-delivery-website
```

### Backend Setup
1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the backend server:
   ```bash
   npm run start
   ```

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

### Admin Panel Setup
1. Access the admin panel by logging in with admin credentials (can be configured in the database).

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payment Gateway**: Stripe

## Folder Structure
```
food-delivery-website/
├── backend/
│   ├── models/       # Mongoose models
│   ├── routes/       # API routes
│   ├── controllers/  # Business logic
│   └── server.js     # Entry point for backend
├── frontend/
│   ├── src/
│   │   ├── components/ # Reusable components
│   │   ├── pages/      # Page components
│   │   └── App.js      # Main app component
│   └── package.json
└── README.md
```







