# Nikhils295-Blinkit-Full-Stack-e-commerce


# Binkeyit Full Stack MERN App

A complete clone of the popular quick-commerce platform Blinkit, built with modern web technologies. This full-stack application replicates the core functionality of instant grocery delivery with a clean, responsive user interface.

## Features

- User Authentication: Secure login/signup with JWT tokens
- Product Catalog: Browse groceries and essentials by categories
- Shopping Cart: Add, remove, and modify items with real-time updates
- Order Management: Place orders with delivery tracking
- Search & Filter: Find products quickly with advanced filtering
- Responsive Design: Optimized for desktop, tablet, and mobile devices
- Admin Panel: Manage products, orders, and users
- Payment Integration: Secure payment processing
- Real-time Updates: Live cart and order status updates

## Tech Stack

### Frontend
- React.js - Component-based UI library
- CSS3/SCSS - Styling and animations
- JavaScript (ES6+) - Modern JavaScript features
- Axios - HTTP client for API calls

### Backend
- Node.js - Runtime environment
- Express.js - Web application framework
- JWT - Authentication and authorization
- Bcrypt - Password hashing

### Database
- MongoDB - NoSQL database for data storage
- Mongoose - ODM for MongoDB

## Prerequisites

Before running this project, make sure you have the following installed:

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local installation or MongoDB Atlas)
- Git

## Quick Start

### 1. Clone the Repository
bash
git clone https://github.com/Nikhils295/Blinkit-Full-stack-E-Commerce.git
cd Blinkit-Full-stack-E-Commerce


### 2. Install Dependencies

#### Backend Setup
bash
# Navigate to backend directory
cd backend
npm install


#### Frontend Setup
bash
# Navigate to frontend directory (in a new terminal)
cd frontend
npm install


### 3. Environment Configuration

Create a .env file in the backend directory:
env
# Database
MONGODB_URI=mongodb://localhost:27017/blinkit

# JWT Secret
JWT_SECRET=your_super_secret_jwt_key_here

# Server Configuration
PORT=5000
NODE_ENV=development

# Payment Gateway (if applicable)
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_SECRET=your_razorpay_secret


Create a .env file in the frontend directory:
env
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key


### 4. Database Setup

Make sure MongoDB is running on your system, or use MongoDB Atlas for cloud database.

### 5. Run the Application

#### Start Backend Server
bash
cd backend
npm start
# or for development with auto-restart
npm run dev


#### Start Frontend Development Server
bash
# In a new terminal
cd frontend
npm start


The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## Project Structure


Blinkit-Full-stack-E-Commerce/
├── backend/
│   ├── controllers/         # Route controllers
│   ├── models/             # Database models
│   ├── routes/             # API routes
│   ├── middleware/         # Custom middleware
│   ├── config/            # Database and app configuration
│   ├── utils/             # Utility functions
│   └── server.js          # Main server file
├── frontend/
│   ├── public/            # Static files
│   ├── src/
│   │   ├── components/    # Reusable components
│   │   ├── pages/         # Page components
│   │   ├── context/       # React context
│   │   ├── utils/         # Utility functions
│   │   ├── styles/        # CSS/SCSS files
│   │   └── App.js         # Main App component
│   └── package.json
└── README.md


## Available Scripts

### Backend
bash
npm start          # Start production server
npm run dev        # Start development server with nodemon
npm test           # Run tests


### Frontend
bash
npm start          # Start development server
npm run build      # Build for production
npm test           # Run tests
npm run eject      # Eject from Create React App

## Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## License

This project is for educational purposes. Please respect the original Blinkit brand and trademarks.

## Author

Nikhil Saxena
- GitHub: @Nikhils295

## Acknowledgments

- Blinkit for the design inspiration
- React and Node.js communities for excellent documentation
- All contributors who help improve this project

Star this repository if you find it helpful!
