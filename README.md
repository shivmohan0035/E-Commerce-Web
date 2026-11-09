# Scalable Digital Commerce Platform – Backend

A scalable and secure E-Commerce Backend built using **Node.js, Express.js, and MongoDB**. This backend provides RESTful APIs for user authentication, product management, order processing, payment integration, and business analytics.

## 🚀 Features

- **Authentication & Authorization** – Secure user authentication using JWT and password hashing with bcrypt.
- **User Management** – User registration, login, and profile management.
- **Product Management** – Create, update, delete, and retrieve products.
- **Order Management** – Handle customer orders and order tracking.
- **Payment Integration** – Payment processing using Razorpay.
- **Image Upload** – Cloudinary integration for product image storage.
- **Admin Authorization** – Role-based access control for administrative operations.
- **Analytics Dashboard** – APIs for business and sales analytics.
- **RESTful APIs** – Structured and scalable API architecture.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Node.js | Backend runtime |
| Express.js | Backend framework |
| MongoDB | NoSQL database |
| Mongoose | Database modeling |
| JWT | Authentication |
| bcryptjs | Password hashing |
| Cloudinary | Image storage |
| Razorpay | Payment gateway |
| Nodemailer | Email services |

## 📁 Project Structure

```text
backend/
│
├── config/
│   ├── cloudinary.js
│   └── db.js
│
├── controllers/
│   ├── analyticsController.js
│   ├── authController.js
│   ├── orderController.js
│   ├── paymentController.js
│   └── productController.js
│
├── middleware/
│   ├── adminMiddleware.js
│   └── authMiddleware.js
│
├── models/
│   ├── Order.js
│   ├── Product.js
│   ├── Review.js
│   └── User.js
│
├── routes/
│   ├── analyticsRoutes.js
│   ├── authRoutes.js
│   ├── orderRoutes.js
│   ├── paymentRoutes.js
│   └── productRoutes.js
│
├── .env
├── package.json
└── server.js
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to Backend

```bash
cd backend
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the backend directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret

EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

Never upload your actual `.env` file or secret credentials to GitHub.

### 5. Start the Server

```bash
npm run dev
```

Or, if you don't have a development script:

```bash
node server.js
```

The backend server will run at:

```text
http://localhost:5000
```

## 🔐 Security

- JWT-based authentication.
- Password hashing using bcrypt.
- Protected routes using authentication middleware.
- Admin-only access to restricted operations.
- Environment-based secret management.

## 📌 Core Modules

| Module | Responsibility |
|---|---|
| Authentication | Registration, login, user authorization |
| Products | Product CRUD operations |
| Orders | Order creation and management |
| Payments | Payment processing |
| Analytics | Business and sales statistics |
| Reviews | Product review management |

## 👨‍💻 Developer

**Shivmohan Chaurasia**

B.Tech – Computer Science & Engineering (AI & ML)

- GitHub: [Your GitHub Profile](https://github.com/)
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/)

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub!

---

**Built with ❤️ using Node.js, Express.js, and MongoDB.**
