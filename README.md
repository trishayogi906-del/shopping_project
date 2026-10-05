# ShopEase Backend

This is the backend of **ShopEase**, an e-commerce web application.

The backend provides APIs for user authentication, product management, and other e-commerce related features.

## 🚀 Features

- User registration and login
- User authentication using JWT
- Access token and refresh token
- Password hashing using bcrypt
- Protected routes
- Cookie-based authentication
- MongoDB database integration
- Mongoose models
- Error handling
- API response handling
- CORS configuration
- Environment variable configuration
- Cloudinary integration for image uploads

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Cloudinary
- dotenv
- cookie-parser
- CORS

## 📁 Project Structure

```text
backend/
│
├── src/
│   ├── controllers/
│   ├── db/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── app.js
│
├── .env
├── .gitignore
├── package.json
├── package-lock.json
└── server.js
```

## ⚙️ Installation

Clone the repository:

```bash
git clone git@github.com:trishayogi906-del/ShopEase.git
```

Go to the backend folder:

```bash
cd ShopEase
```

Install dependencies:

```bash
npm install
```

## 🔐 Environment Variables

Create a `.env` file in the root directory and add the required environment variables.

Example:

```env
PORT=8000

MONGODB_URI=your_mongodb_connection_string

ACCESS_TOKEN_SECRET=your_access_token_secret
ACCESS_TOKEN_EXPIRY=your_access_token_expiry

REFRESH_TOKEN_SECRET=your_refresh_token_secret
REFRESH_TOKEN_EXPIRY=your_refresh_token_expiry

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

> Never upload your `.env` file or secret keys to GitHub.

## ▶️ Run the Project

Start the development server:

```bash
npm run dev
```

The backend will run on:

```text
http://localhost:8000
```

The port may be different depending on your `.env` configuration.

## 🔑 Authentication

ShopEase uses **JWT-based authentication**.

The application uses:

- Access Token
- Refresh Token
- HTTP-only cookies
- Protected middleware

This helps protect authenticated routes and user information.

## 🗄️ Database

The project uses **MongoDB** with **Mongoose** for database management.

MongoDB stores application data such as:

- Users
- Products
- Orders
- Other e-commerce related data

## 📦 API

The backend follows a REST API structure.

Example API categories:

```text
/api/users
/api/products
/api/orders
```

The exact routes may change as the project grows.

## 🎯 Project Goal

The main goal of this project is to build a complete e-commerce backend while learning how real-world backend applications are structured.

It focuses on:

- REST APIs
- Authentication
- Database management
- Middleware
- Error handling
- File uploads
- Secure API development

## 🚧 Future Improvements

Future features may include:

- Product search and filtering
- Shopping cart APIs
- Order management
- Payment gateway integration
- Admin dashboard APIs
- Product reviews and ratings
- Wishlist functionality
- Advanced authorization

## 👩‍💻 Author

**Trisha Yogi**

GitHub: https://github.com/trishayogi906-del
