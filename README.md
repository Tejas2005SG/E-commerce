<h1 align="center">E-Commerce Store 🛒</h1>



This project is a fully functional e-commerce platform built using the MERN stack. It includes features like user authentication, product management, a shopping cart, and secure payment processing with Stripe. The platform is optimized for performance and scalability, making it suitable for production-grade deployments.

🔗 Get the FLOWCHART OF THIS APPLICATION HERE ----->> [E-commerce](https://app.eraser.io/workspace/m4P3FpVBcoo8CmA0KD1P)

## Features

### Customer Features
- User-friendly product browsing and search.
- Add products to the shopping cart and manage quantities.
- Secure checkout process with Stripe payment integration.
- Order history and tracking.

### Admin Features
- Dashboard for managing products, orders, and users.
- Sales analytics for better decision-making.
- Manage inventory with CRUD operations.

### Technical Features
- *MERN Stack*: MongoDB, Express.js, React.js, and Node.js.
- *Authentication*: Secure login, signup, and session management.
- *Payment Gateway*: Integrated with Stripe for real-time payments.
- *Optimizations*: Redis for caching, reducing database load.
- *Media Management*: Cloudinary for scalable image storage.
- *Frontend Styling*: Tailwind CSS for responsive and modern designs.



## Project Structure

### Backend
- *server.js*: Entry point for the Node.js server.
- *controllers*: API logic for handling requests.
- *routes*: API endpoints for various resources.
- *models*: MongoDB schemas for database management.
- *middleware*: Custom middleware for authentication and error handling.
- *lib*: Utility functions for reusable code.

### Frontend
- *src*: React components, pages, and state management.
- *tailwind.config.js*: Tailwind CSS configuration for custom styles.
- *vite.config.js*: Vite for fast builds and optimized development.



## Installation and Setup

### Prerequisites
- Node.js and npm installed on your system.
- MongoDB server or cloud database (e.g., MongoDB Atlas).
- Stripe account for payment integration.

### Steps
1. Clone the repository:
   ```
   git clone https://github.com/Tejas2005SG/mern-ecommerce.git
   cd mern-ecommerce
   ```
2. Install dependencies for both frontend and backend:
    ```
    cd backend
    npm install
    cd ../frontend
    npm install
    ```
3. Configure environment variables:
   Create a .env file in the backend folder with the following keys:
    
  ### Setup .env file

```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```
    
    
4. Run the application:
   Start the backend:
    ```
    cd backend
    npm run dev
    ```
    
  Start the frontend:
    ```
    cd frontend
    npm run dev
    ```
5. Open your browser and navigate to http://localhost:5000 (or the port defined in the configuration).

<h1 align="center">Technologies Used</h1>
<ol>
  <li>Frontend: React.js, Tailwind CSS, Vite</li>
  <li>Backend: Node.js, Express.js</li>
  <li>Database: MongoDB</li>
  <li>Caching: Redis</li>
  <li>Payment Gateway: Stripe</li>
  <li>Media Storage: Cloudinary</li>
  <li>Authentication: JWT-based secure login system</li>
</ol>

<h1 align="center">Future Enhancements</h1>
<ol>
  <li>E-mail Verification, Welcome E-mail and many Email services</li>
  <li>Adding Filter option for better user experience</li>
</ol>






