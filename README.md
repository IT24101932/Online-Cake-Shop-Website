🎂 Online Cake Shop - Full Stack Web Application

A modern and high-performance web application designed for seamless cake ordering, delivery tracking, and administrative management.

📌 Project Overview
The Online Cake Shop is a full-stack application that provides a delightful experience for users to browse, customize, and order cakes and accessories. It also includes a robust management system for admins and a dedicated dashboard for delivery drivers.

This system supports three primary user roles:

| Role | Description |
| :--- | :--- |
| 🍰 **Customer** | Browses cakes, places orders, and tracks deliveries |
| 🚚 **Delivery Driver** | Manages assigned deliveries and updates status |
| 🛡️ **Administrator** | Manages inventory, orders, system reports, and users |

🎯 Objectives
- Provide a smooth and intuitive cake ordering process.
- Enable real-time inventory and order management.
- Streamline delivery logistics with driver-specific features.
- Offer secure user authentication and personalized experiences.
- Generate detailed business reports for better decision-making.

🛠️ Technology Stack
| Category | Technology |
| :--- | :--- |
| **Frontend** | React 19, Vite, Tailwind CSS 4, Framer Motion |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose ODM) |
| **Authentication** | JWT (JSON Web Tokens), Bcryptjs, Google OAuth |
| **Communication** | Axios, Nodemailer (OTP Verification) |
| **Version Control** | Git & GitHub |
| **IDE** | VS Code |

⚙️ Key Features
🍰 Customer Features
- 📋 **Authentication**: Secure login/register with OTP verification and Google OAuth.
- 🎂 **Browse Cakes**: Explore a wide variety of cakes and accessories with rich details.
- 🛒 **Ordering System**: Seamless checkout process for cakes and accessories.
- 💳 **Online Payments**: Integrated payment simulation for order completion.
- ⭐ **Reviews & Feedback**: Rate cakes and provide feedback on the overall service.
- 🕒 **Order History**: Track past orders and current delivery status.

🚚 Delivery Driver Features
- 📍 **Assigned Deliveries**: View a list of orders ready for delivery.
- 🔄 **Status Updates**: Update delivery status (Pending, Out for Delivery, Completed).
- 🧭 **Navigation**: Access customer delivery information for efficient routing.

🛡️ Administrator Features
- 📊 **Dashboard**: Overview of system activity and key metrics.
- 📦 **Inventory Management**: Full CRUD operations for cakes and accessories.
- 📑 **Order Management**: Monitor and process all incoming customer orders.
- 👥 **User & Driver Management**: Manage customer accounts and assign tasks to drivers.
- 📈 **System Reports**: Generate usage and feedback reports for business analysis.

🖥️ System Modules
- **User Management**: Auth, profiles, and role-based access control.
- **Cake & Product Management**: Catalog and inventory control.
- **Order Processing**: Workflow from cart to completion.
- **Payment & Transaction**: Handling secure order payments.
- **Delivery & Logistics**: Managing the delivery pipeline.
- **Reporting & Analytics**: Data-driven insights for administrators.

🗂️ Project Structure
```text
online-cake-shop-frontend/
├── src/
│   ├── components/  # Reusable UI components
│   ├── pages/       # Page-level components (Admin, Driver, User)
│   ├── utils/       # Helper functions and API configuration
│   └── App.jsx      # Main routing and application entry
└── tailwind.config.js

online-cake-shop-backend/
├── controllers/     # Business logic for API endpoints
├── models/          # MongoDB schemas (User, Cake, Order, etc.)
├── Routes/          # API route definitions
├── middleware/      # Auth and error-handling middleware
└── index.js         # Entry point for the Express server
```

🚀 Getting Started
Step 1 — Clone the Repository
```bash
git clone https://github.com/yourusername/online-cake-shop.git
cd online-cake-shop
```

Step 2 — Backend Setup
```bash
cd online-cake-shop-backend
npm install
# Create a .env file and add your Mongo_Url, JWT_SECRET, etc.
npm start
```

Step 3 — Frontend Setup
```bash
cd ../online-cake-shop-frontend
npm install
npm run dev
```

---

## 📊 Future Enhancements
- 📱 **Mobile App**: Cross-platform mobile version using React Native.
- 📡 **Real-time Tracking**: Live map-based delivery tracking for customers.
- 🤖 **AI Recommendations**: Personalized cake suggestions based on user preference.
- 💳 **Payment Integration**: Integration with Stripe or PayPal for real transactions.

---

## 👥 Team Members
| Student ID | Name | Role |
| :--- | :--- | :--- |
| [ID] | [Your Name] | Lead Developer |
| [ID] | [Team Member 2] | Backend Specialist |
| [ID] | [Team Member 3] | UI/UX Designer |

---

## 📬 Contact
**Developer:** [Your Name]
📧 **Email:** [your.email@example.com]
🌍 **Location:** Sri Lanka 🇱🇰

---

## ⭐ Support
If you find this project helpful:
- ⭐ **Star** this repository
- 🍴 **Fork** this repository
