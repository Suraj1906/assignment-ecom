# 🛒 Grocery Delivery Website  

![MERN](https://img.shields.io/badge/MERN-Full%20Stack-green?style=flat-square&logo=mongodb)
![React](https://img.shields.io/badge/Frontend-React.js-blue?style=flat-square&logo=react)
![Node.js](https://img.shields.io/badge/Backend-Node.js-success?style=flat-square&logo=node.js)
![Tailwind](https://img.shields.io/badge/UI-TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css)
![Stripe](https://img.shields.io/badge/Payments-Stripe-blueviolet?style=flat-square&logo=stripe)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

A **full-stack grocery delivery platform** built using the **MERN stack**, featuring secure authentication, responsive UI, and **Stripe API** integration for online payments.  
Users can browse grocery items, manage their carts, place orders, and pay securely — while admins can manage products and track orders in real time.

---

## 🚀 Features  

### 👤 User Features  
- 🔐 JWT-based authentication (Signup/Login/Logout)  
- 🔑 Secure password encryption using **bcrypt**  
- 🛍️ Browse products with category filters and related suggestions  
- 🛒 Add, update, or remove products in the cart (**full CRUD functionality**)  
- 💳 Seamless checkout using **Stripe API**  
- 📱 Fully responsive UI built with **React.js + Tailwind CSS**

### 🛠️ Admin Features  
- 🧾 Add, edit, and delete grocery products  
- 📦 Manage and track 100+ products  
- 📊 Real-time order tracking via admin dashboard  

### ⚙️ Performance & Architecture  
- ⚡ Improved frontend performance by **30%** using **React Context API**  
- 🧩 Scalable **MongoDB–Express–Node.js** backend  
- 🌐 RESTful APIs for authentication, products, and orders  

---

## 🧰 Tech Stack  

| Category | Technology |
|-----------|-------------|
| **Frontend** | React.js, Tailwind CSS, Context API |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (MongoDB Atlas) |
| **Authentication** | JWT, bcrypt |
| **Payments** | Stripe API |
| **Deployment** | Frontend – Vercel, Backend – Render |

---

## ⚙️ Setup Instructions  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Suraj1906/assignment-ecom
cd assignment-ecom
```
### 2️⃣ Install Dependencies
Backend:
```bash
cd server
npm install
```
Frontend:
```bash
cd ../client
npm install
```
### 3️⃣ Configure Environment Variables  

This project includes **sample `.env` files** for quick setup.  
All variables except **Stripe keys** have pre-filled test values — you’ll need to add your own Stripe credentials.  

> ⚠️ **Important:**  
> - Stripe keys are **not included** for security reasons.  
> - Add your own **Stripe public and secret keys** to enable payment functionality.
Example: /server/.env

```bash
PORT=4000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key  # add your own
```
Example: /client/.env
```bash
VITE_BACKEND_URL=http://localhost:4000
VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key  # add your own
```
### 4️⃣ Run the Application
Start backend:
```bash
cd server
npm run server
```
Start frontend:
```bash
cd ../client
npm run dev
```
Now open your browser and visit 👉 http://localhost:5173

## 🌍 Live Demo  

🔗 **Frontend:** 👉 [Click Here To See](https://greencart-deploy-ixed.vercel.app/)


## 📸 Screenshots  

<h3>🛍️ Product Grid Page</h3>
Displays all available grocery items with category filters and “Add to Cart” options.  

<img width="1261" height="680" alt="product grid" src="https://github.com/user-attachments/assets/97d17e52-fbd3-4ae2-ab5f-4087c5a5649d" />


<h3>🛒 Cart Page</h3>
Shows added products, quantity controls, and total checkout price.  


<img width="1257" height="616" alt="Cart Page" src="https://github.com/user-attachments/assets/5bb2601f-ff9b-4ad8-ab23-f063e6bfb737" />


<h3>🧾 Receipt Page</h3>
Displays order confirmation details and payment summary after successful checkout.  


<img width="1242" height="463" alt="my orders" src="https://github.com/user-attachments/assets/ee3837b6-0abe-45c8-b821-474f019b085d" />








## 👨‍💻 Author  

**Suraj Bhardwaj**  
🎓 MCA Student | 💻 Fullstack Developer (MERN)  

🔗 [GitHub](https://github.com/Suraj1906) | [LinkedIn](https://www.linkedin.com/in/suraj-bhardwaj-1906)  
📧 **Email:** surajbhardwaj5918@gmail.com


---

## 📜 License  

This project is licensed under the **MIT License** — feel free to use and modify it with proper attribution.




