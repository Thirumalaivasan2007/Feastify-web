<div align="center">
  <h1>🍔 Feastify - Premium Food Delivery Platform</h1>
  <p>A full-stack, enterprise-grade food ordering experience powered by Node.js, Express, and MongoDB.</p>

  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
</div>

<br />

### 🚀 Live Demo
[Experience Feastify Here](https://feastify-food-web.vercel.app)

---

## ✨ Key Features

*   **🛒 AI Smart Recommendations**: A dynamic cross-selling engine that suggests related items (e.g., Coke with Biryani) directly in the cart.
*   **📍 Geolocation Integration**: One-click address auto-fill using the Nominatim OpenStreetMap API during checkout.
*   **📧 Automated Email Alerts**: Real-time email notifications powered by Nodemailer for new signups, order placements, and security alerts.
*   **🔐 Enterprise-Level Security**: Secure admin dashboard with bcrypt password hashing to prevent data breaches.
*   **📈 Real-Time Admin Dashboard**: Monitor live orders, track revenue, manage menu items, and view registered users seamlessly.
*   **📱 Fully Responsive**: Dark-themed, premium UI that works perfectly across mobile, tablet, and desktop devices.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (Modern ES6+)
- **Backend Proxy**: Vercel Serverless Functions (SMTP Bypass)
- **Primary Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose ODM)
- **Security**: Bcrypt.js password hashing

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18.x or higher)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) Account

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Thirumalaivasan2007/Feastify-web.git
cd Feastify-web
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configuration
Create a `.env` in the root folder with:
```env
PORT=3000
MONGO_URI=your_mongodb_atlas_uri
EMAIL_USER=your_gmail@gmail.com
EMAIL_PASS=your_16_digit_app_password
ADMIN_EMAIL=your_admin@example.com
ADMIN_PASSWORD=your_secure_password
```

### 4. Start the Application
```bash
npm start
```

## 📂 Project Structure

```plaintext
├── api/             # Vercel Serverless Functions (Email Proxy)
├── models/          # Mongoose database schemas (User, Food, Category, Order)
├── public/          # Client-side web pages, CSS styles, and UI Javascript
├── db.js            # MongoDB database connection configuration
├── server.js        # Main Express routing and server logic
└── package.json     # Node script definitions and dependencies
```

---

## 👨‍💻 Developed By

**Thirumalaivasan T**  
*B.E. Computer Science Engineering Student & Full-Stack Developer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/t-thirumalai-944tv)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://thirumalaivasan-portfolio-one.vercel.app)

---
<div align="center">
  <i>Developed with ❤️ for food lovers. Mass pannunga boss! 🚀🔥</i>
</div>
