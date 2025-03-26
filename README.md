# E-Commerce MERN Stack Application

A full-featured e-commerce platform built with the MERN (MongoDB, Express.js, React.js, Node.js) stack, featuring both customer-facing shopping interfaces and admin management capabilities.

[Demo](https://e-commerce-mern-33mx.vercel.app/)

![alt](https://github.com/sakshamagarwalm2/E-Commerce-MERN/blob/main/Public/Screenshot%202025-03-26%20235914.png)


![alt](https://github.com/sakshamagarwalm2/E-Commerce-MERN/blob/main/Public/Screenshot%202025-03-26%20235935.png)


![alt](https://github.com/sakshamagarwalm2/E-Commerce-MERN/blob/main/Public/Screenshot%202025-03-26%20235949.png)


## 🌟 Features

### Customer Features
- User authentication (signup, login)
- Product browsing and search
- Product details with reviews
- Shopping cart management
- Secure checkout process with PayPal integration
- Order tracking
- Account management
- Review submission

### Admin Features
- Product management (CRUD operations)
- Order management
- User management
- Product category management
- Review moderation
- Sales analytics

## 🛠️ Technologies Used

### Frontend
- React.js
- Redux Toolkit for state management
- Tailwind CSS for styling
- Radix UI for accessible components
- 
![alt](https://github.com/sakshamagarwalm2/E-Commerce-MERN/blob/main/Public/Screenshot%202025-03-27%20000017.png)
- React Router for navigation
- Axios for API requests

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Cloudinary for image storage
- PayPal API integration

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- MongoDB
- PayPal Developer Account
- Cloudinary Account

### Installation

1. Clone the repository
```bash
git clone https://github.com/sakshamagarwalm2/E-Commerce-MERN.git
cd E-Commerce-MERN
```

2. Install dependencies for both frontend and backend
```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. Set up environment variables
```bash
# In server directory, create .env file with:
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret

# In client directory, create .env file with:
VITE_API_URL=http://localhost:5000
VITE_PAYPAL_CLIENT_ID=your_paypal_client_id
```

4. Run the application
```bash
# Run backend server
cd server
npm run dev

# Run frontend in another terminal
cd client
npm run dev
```

## 📱 Application Structure

### Client-side Structure
```
client/
├── src/
│   ├── components/     # Reusable components
│   ├── pages/         # Page components
│   ├── store/         # Redux store configuration
│   ├── lib/           # Utility functions
│   └── assets/        # Static assets
```

### Server-side Structure
```
server/
├── controllers/       # Route controllers
├── models/           # Database models
├── routes/           # API routes
├── helpers/          # Helper functions
└── middleware/       # Custom middleware
```

## 🔐 API Endpoints

### Auth Routes
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login user
- `GET /api/auth/profile` - Get user profile

- 
![alt](https://github.com/sakshamagarwalm2/E-Commerce-MERN/blob/main/Public/Screenshot%202025-03-27%20000030.png)

### Product Routes
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get single product
- `POST /api/products` - Create product (Admin)
- `PUT /api/products/:id` - Update product (Admin)
- `DELETE /api/products/:id` - Delete product (Admin)

### Order Routes
- `POST /api/orders` - Create order
- `GET /api/orders/me` - Get user orders
- `GET /api/orders/:id` - Get order by ID
- `PUT /api/orders/:id/pay` - Update order to paid

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Live Demo

Check out the live demo: [E-Commerce MERN](https://e-commerce-mern-33mx.vercel.app/)

## 👤 Contact

Saksham Agarwal - [GitHub](https://github.com/sakshamagarwalm2)
