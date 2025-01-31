![E-Commerce Homepage](thumb.png)

# E-Commerce Website

An advanced e-commerce platform built using the **MERN stack**, **Redux**, and **Tailwind CSS**, offering a modern, scalable, and responsive shopping experience.

---

## 🚀 Features

### User Features

- 🛒 **Product Browsing**: View products with images, descriptions, and prices.
- 🔍 **Search & Filter**: Search products by name and filter by category, price range, etc.
- 🛍️ **Add to Cart**: Add and remove items from a shopping cart.
- 💳 **Checkout Process**: Complete orders using a secure payment gateway (e.g., Stripe/PayPal).
- 🔐 **User Authentication**: Sign up, log in, and manage profiles using JWT-based authentication.
- ⭐ **Product Reviews**: Leave ratings and reviews for products.

### Admin Features

- 📦 **Product Management**: Add, edit, and delete products.
- 📊 **Order Management**: View and update the status of customer orders.
- 👤 **User Management**: Manage user accounts and roles.

### Design & Responsiveness

- 🎨 **Tailwind CSS**: Fully responsive design with a clean and modern UI.
- 📱 Optimized for mobile, tablet, and desktop.

---

## 🛠️ Tech Stack

### Frontend

- **React.js**: Frontend framework for building user interfaces.
- **Redux**: State management for consistent and scalable application state.
- **Tailwind CSS**: For styling with a utility-first approach.

### Backend

- **Node.js**: Backend runtime for server-side JavaScript.
- **Express.js**: Lightweight and flexible backend framework.
- **MongoDB**: NoSQL database for storing product, user, and order information.
- **JWT**: Secure user authentication and session management.

---

## ⚙️ Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/ecommerce-website.git
   cd ecommerce-website

   ```

2. **Install Dependencies**

- Install Server Side dependencies

  ```bash
  cd backend
  npm install

  ```

- Install Client Side dependencies
  ```bash
  cd frontend
  npm install
  ```

3. **Set Up Environment Variables** Create a .env file & add the following:
   PORT=5000
   MONGO_URI=<your-mongo-uri>
   JWT_SECRET=<your-jwt-secret>
   STRIPE_SECRET_KEY=<your-stripe-secret-key>

4. **Run the Application**

```bash
    npm run dev
```
