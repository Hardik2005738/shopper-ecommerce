🛍️ Shooper Ecommerce
Shooper is a full-stack ecommerce web application that provides a customer-facing online store and an admin dashboard for product management.
Built with React, Node.js, Express, and MongoDB.

📁 Project Structure
graphql
Copy
Edit
Full_Stack_Ecommerce/
 ├── backend/   # Node.js + Express REST API server
 ├── frontend/  # Customer-facing React app
 └── admin/     # Admin dashboard React app
✨ Features
Customer Storefront

Browse and search products

Add items to cart

Checkout with integrated payment gateway

Admin Panel

Secure admin dashboard

Add new products

View and manage product listings

Manage orders and transactions

Backend API

RESTful API with Node.js & Express

MongoDB database for storing products, users, and orders

⚙️ Tech Stack
Frontend: React

Backend: Node.js, Express

Database: MongoDB

Version Control: Git, GitHub

🚀 Getting Started
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/YOUR-USERNAME/shooper-ecommerce.git
cd Full_Stack_Ecommerce
2️⃣ Install Dependencies
bash
Copy
Edit
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Install admin panel dependencies
cd ../admin
npm install
3️⃣ Run the Applications
bash
Copy
Edit
# Start backend server
cd backend
npm start

# Start frontend (customer store)
cd ../frontend
npm start

# Start admin dashboard
cd ../admin
npm start
🔑 Environment Variables
Before starting the backend, create a .env file in the backend/ directory:

ini
Copy
Edit
MONGODB_URI=your_mongodb_connection_string
PORT=4000
Replace your_mongodb_connection_string with the actual MongoDB URI.

📚 How To Use
Frontend: Available to customers for browsing products, adding to cart, and making purchases.

Admin Panel: Accessible to admins to add/manage products and view orders.

✅ Project Highlights
Modern responsive UI

Full CRUD for product management

Integrated cart and checkout flow


📜 License
This project is licensed under the MIT License.

✍️ Author
Made by Hardik Rangi
