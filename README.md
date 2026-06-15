# 🛒 GreenCart

---

## 🌱 About GreenCart

**GreenCart** is a full-stack **MERN Grocery Delivery Platform** designed to provide a seamless online grocery shopping experience.

Users can browse products, manage their carts, place orders, save delivery addresses, and make payments securely. Sellers can manage inventory, add products, and track incoming orders through a dedicated dashboard.

The platform focuses on:

* Fresh grocery shopping experience
* Secure authentication
* Online & Cash on Delivery payments
* Seller inventory management
* Responsive modern UI
* Cloud-based image storage

---

## 🚀 Live Demo

🌐 **Website:**
https://greenigo.vercel.app/

🌐 **Website backend:**
https://greencart-backend-nu-virid.vercel.app/

---

## 🎯 Key Features

### 👤 User Features

* User Registration & Login
* JWT Authentication
* Browse Products
* Product Categories
* Product Search
* Product Details Page
* Shopping Cart Management
* Address Management
* Order Placement
* Order Tracking
* Order History

---

### 🛍️ Seller Features

* Seller Authentication
* Add New Products
* Upload Product Images
* Manage Product Inventory
* View Customer Orders
* Order Management Dashboard

---

### 💳 Payment Features

* Stripe Payment Gateway Integration
* Cash on Delivery (COD)
* Secure Checkout Flow

---

### ☁️ Cloud Features

* Cloudinary Image Uploads
* MongoDB Database Storage
* Vercel Deployment

---

## 🛠️ Tech Stack

| Category       | Technologies        |
| -------------- | ------------------- |
| Frontend       | React.js, Vite      |
| Styling        | Tailwind CSS        |
| Backend        | Node.js, Express.js |
| Database       | MongoDB             |
| Authentication | JWT, Cookies        |
| Image Storage  | Cloudinary          |
| Payments       | Stripe              |
| Deployment     | Vercel              |
| HTTP Client    | Axios               |

---

# 📁 Project Structure

```bash
GreenCart/
│
├── client/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── seller/
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── ProductCard.jsx
│   │   │   └── Login.jsx
│   │   │
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── AllProducts.jsx
│   │   │   ├── ProductDetails.jsx
│   │   │   ├── ProductCategory.jsx
│   │   │   ├── Cart.jsx
│   │   │   ├── AddAddress.jsx
│   │   │   ├── MyOrders.jsx
│   │   │   └── seller/
│   │   │
│   │   ├── context/
│   │   │   └── AppContext.jsx
│   │   │
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── configs/
│   │   ├── db.js
│   │   └── cloudinary.js
│   │
│   ├── controllers/
│   │
│   ├── middlewares/
│   │
│   ├── models/
│   │   ├── User.js
│   │   ├── Product.js
│   │   ├── Address.js
│   │   └── Order.js
│   │
│   ├── routes/
│   │   ├── userRoute.js
│   │   ├── sellerRoute.js
│   │   ├── productRoute.js
│   │   ├── cartRoute.js
│   │   ├── addressRoute.js
│   │   └── orderRoute.js
│   │
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/anaydeshpande1749/GREENCART.git
cd GREENCART
```

---

## Client Setup

```bash
cd client
npm install
```

Create `.env`

```env
VITE_BACKEND_URL=YOUR_BACKEND_URL
VITE_CURRENCY=₹
```

Run:

```bash
npm run dev
```

---

## Server Setup

```bash
cd server
npm install
```

Create `.env`

```env
MONGODB_URI=
JWT_SECRET=

SELLER_EMAIL=
SELLER_PASSWORD=

STRIPE_SECRET_KEY=

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

FRONTEND_URL=
```

Run:

```bash
npm start
```

---

# 🛒 User Flow

1. User signs up / logs in
2. Browse products
3. Search or filter by category
4. Add items to cart
5. Select delivery address
6. Choose payment method
7. Place order
8. Track orders

---

# 🧑‍💼 Seller Flow

1. Seller logs in
2. Opens Seller Dashboard
3. Adds products
4. Uploads product images
5. Manages inventory
6. Views customer orders
7. Processes deliveries

---

# 📽️ Demo Video

🎥 Demo Video:

https://github.com/user-attachments/assets/34e66bf6-c952-46e1-9e13-c8fd2886305d


---

# 🖼️ Screenshots

## 🏠 Home Page

<img width="1900" height="912" alt="Home page" src="https://github.com/user-attachments/assets/786425e9-799f-4d51-ab7b-57a702c53143" />

---

## 🛍️ Products Page

<img width="1896" height="917" alt="products" src="https://github.com/user-attachments/assets/1be55a40-91d3-4324-9efa-a4f928488236" />


---

## 🧑‍💼 Seller Dashboard

<img width="1902" height="917" alt="seller1" src="https://github.com/user-attachments/assets/2959e46c-c026-4883-a007-f46c46d8b84f" />

<img width="1905" height="915" alt="seller2" src="https://github.com/user-attachments/assets/f8c1ae19-a9b2-4548-bf09-ab314d0fd001" />

<img width="1895" height="907" alt="seller3" src="https://github.com/user-attachments/assets/fee5acd6-b818-4b05-a458-b154c2482b20" />


---

# 📚 Learning Outcomes

* MERN Stack Development
* REST API Design
* JWT Authentication
* Stripe Payment Integration
* Cloudinary Media Management
* MongoDB Data Modeling
* Context API State Management
* Full Stack Deployment on Vercel

---

# 🔮 Future Enhancements

* Real-time Order Tracking
* Wishlist Functionality
* Product Reviews & Ratings
* Email Notifications
* AI-Based Product Recommendations
* Multi-Vendor Marketplace Support
* PWA Mobile Experience

---

# 👨‍💻 Author

### Anay Deshpande

* GitHub: https://github.com/anaydeshpande1749
* LinkedIn: https://www.linkedin.com/in/anay-deshpande-/

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork the repository
🚀 Share it with others

---

**GreenCart — Fresh Groceries Delivered at Your Doorstep 🌱**
