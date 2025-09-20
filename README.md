<img width="1906" height="975" alt="image" src="https://github.com/user-attachments/assets/6f27c539-62d4-4188-8fdc-7248af0ce2bf" /># 🛍️ Trendora – MERN E-Commerce Store

Trendora is a **full-stack e-commerce web application** built with the **MERN stack (MongoDB, Express, React, Node.js)**. It provides a modern online shopping experience with product listings, cart management, user authentication, order processing, and an admin dashboard for managing products and users.

---

## ✨ Features

* 🔐 **User Authentication** (JWT-based login/register)
* 🛒 **Shopping Cart & Checkout**
* 📦 **Order Placement & Payment Integration (PayPal/Stripe-ready)**
* ⭐ **Product Reviews & Ratings**
* 🛍️ **Product Categories** (Mobiles, Laptops, Consoles, Appliances, etc.)
* 🖼️ **Image Upload for Products**
* ⚙️ **Admin Panel** (Manage users, products, orders)
* 📱 **Responsive UI with Bootstrap**
* 🚀 **REST API with Express & MongoDB**

---

## 🛠️ Tech Stack

* **Frontend:** React, Redux, React-Bootstrap
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose ODM)
* **Authentication:** JWT (JSON Web Token)
* **Payments:** PayPal/Stripe Integration
* **Deployment Ready:** Heroku / Vercel / Render

---

## 📂 Project Structure

```
proshop_mern-master/
│── backend/         # Express API & MongoDB models
│── frontend/        # React + Redux frontend
│── uploads/         # Product images
│── .env             # Environment variables
│── package.json     # Scripts & dependencies
│── README.md        # Documentation
```

---

## ⚡ Installation & Setup

1️⃣ Clone the repository:

```bash
git clone https://github.com/your-username/trendora.git
cd trendora
```

2️⃣ Install dependencies:

```bash
# Install backend dependencies
npm install

# Install frontend dependencies
cd frontend
npm install
```

3️⃣ Add environment variables in `.env`:

```env
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
```

4️⃣ Run the app:

```bash
# Run backend + frontend (concurrently)
npm run dev

# Run backend only
npm run server

# Run frontend only
cd frontend
npm start
```

---

## 🗄️ Sample Data

You can load sample products & users into MongoDB:

```bash
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

---

## 🚀 Deployment

* Frontend can be deployed on **Vercel/Netlify**
* Backend + DB can be deployed on **Render/Heroku/Atlas**
* Update `.env` for production configs

---

## 📸 Screenshots

## Home Page
<img width="1889" height="975" alt="image" src="https://github.com/user-attachments/assets/2ca42e00-2389-483b-9bf1-d19e3f363a7e" />

---

## Review & Recommended Products 
<img width="1870" height="972" alt="image" src="https://github.com/user-attachments/assets/282b772b-1c34-4aab-841d-7d9ae43094a9" />

---

## Profile Page
<img width="1906" height="975" alt="image" src="https://github.com/user-attachments/assets/78cdb0d4-4ff2-451c-a564-9a6b36c1fe75" />

---

## Cart Page
<img width="1905" height="976" alt="image" src="https://github.com/user-attachments/assets/d2307283-4f17-4f43-8f36-3df7f8431959" />

---

## Order Page
<img width="1898" height="983" alt="image" src="https://github.com/user-attachments/assets/6d4c6dfe-41d9-4aa6-8891-2254b25951ac" />

---

## Payment Page
<img width="1915" height="964" alt="image" src="https://github.com/user-attachments/assets/74f6cf60-5272-4b23-a8e0-25abfc794c16" />

---

## 🤝 Contributing

1. Fork the repo 🍴
2. Create a feature branch 🌱
3. Submit a Pull Request 🎉
