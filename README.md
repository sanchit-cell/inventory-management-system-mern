
# Inventory Management System

An Inventory Management System built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

### Frontend (React.js)
1. **Dashboard:**
   - Overview of inventory statistics, such as total products, low stock alerts, and recent activities.
2. **Product Management:**
   - Add, update, and delete products.
   - View product details, including name, SKU, category, price, stock levels, and supplier information.
3. **Category Management:**
   - Create and manage product categories.
4. **Supplier Management:**
   - Add and manage supplier information.
5. **Order Management:**
   - Track incoming and outgoing orders.
   - Update order status and details.
6. **Reporting:**
   - Generate reports on inventory levels, sales, and supplier performance.

### Backend (Node.js, Express.js)
1. **RESTful API:**
   - CRUD operations for products, categories, suppliers, and orders.
   - Authentication and authorization using JWT for secure access.
2. **Database Management:**
   - MongoDB for storing product, category, supplier, and order data.
   - Mongoose for schema definitions and data validation.

### Database (MongoDB)
1. **Schemas:**
   - **Product Schema:** Name, SKU, category, price, stock levels, supplier.
   - **Category Schema:** Name, description.
   - **Supplier Schema:** Name, contact details, product list.
   - **Order Schema:** Products, quantities, order status, dates.

### Additional Features
1. **User Authentication:**
   - Sign-up and login functionality.
   - Role-based access control (e.g., admin, manager, staff).
2. **Search and Filtering:**
   - Search products by name, SKU, or category.
   - Filter products by stock levels or supplier.
3. **Notifications:**
   - Alerts for low stock levels or critical updates.
4. **Responsive Design:**
   - Mobile-friendly interface for accessing the system on different devices.

### Tools and Libraries
- **Frontend:**
  - React Router for navigation.
  - Redux for state management.
  - Axios for API calls.
- **Backend:**
  - Express.js for building the API.
  - Mongoose for interacting with MongoDB.
  - Bcrypt for password hashing.
  - JWT for secure token-based authentication.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/inventory-management-system.git
   ```
2. **Install dependencies for the backend:**
   ```bash
   cd inventory-management-system/backend
   npm install
   ```
3. **Install dependencies for the frontend:**
   ```bash
   cd ../frontend
   npm install
   ```

## Usage

1. **Run the backend server:**
   ```bash
   cd backend
   npm start
   ```
2. **Run the frontend server:**
   ```bash
   cd frontend
   npm run dev
   ```

3. **Open the application:**
   Open your browser and navigate to `http://localhost:5173`

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.


