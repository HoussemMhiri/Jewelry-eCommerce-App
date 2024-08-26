# RoyalGem - Jewelry E-commerce App

**RoyalGem** is a comprehensive Jewelry E-commerce application built with the MERN stack. This app provides a full range of e-commerce functionalities, including product filtering, search, authentication, and an admin dashboard.

## Features

### User Features

- **Product Filtering:** Filter products by categories, gender, material, and price.
- **Search Functionality:** Search for products by title or keywords.
- **Product Details:** View detailed information about each product including the story and images.
- **Wishlist:** Save liked products and view them later.
- **Payment Integration:** Secure payment processing with Stripe.
- **Authentication & Authorization:** User authentication, authorization, and logout using JWT tokens.

### Admin Features

- **Dashboard:** Access an admin dashboard with charts and statistics:
  - **User Statistics:** Monthly user statistics.
  - **Sales Statistics:** Total sales and sales per product.
- **User Management:** Manage users, including viewing purchase details.
- **Product Management:** Add, delete, and update products.
- **Authentication:** Secure access to the admin dashboard with authentication.

## Tech Stack

- **Frontend:**
  - React.js
  - Redux for state management
  - MUI (Material-UI) and Ant Design for UI components
  - React Router for navigation
  - Stripe for payment processing
  - React Toastify for notifications
  - Axios for HTTP requests

- **Backend:**
  - Node.js with Express.js
  - MongoDB for database management
  - JWT for authentication and authorization
  - Nodemailer for sending emails

## Installation

### Prerequisites

- Node.js & npm
- MongoDB
- Stripe account for payment integration

### Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/royalgem.git
    cd royalgem
    ```

2. **Install JavaScript dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:**

    - Create a `.env` file in the root directory for both frontend and backend.
    - Add your environment variables for API keys, MongoDB URI, and JWT secret.

    ```env
    REACT_APP_API_URL=http://localhost:5000
    REACT_APP_STRIPE_API_KEY=your_stripe_api_key
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the development server:**

    ```bash
    npm start
    ```

5. **Visit `http://localhost:3000` for the frontend and `http://localhost:5000` for the backend admin dashboard.**

## Usage

- **Browse Products:** Filter and search products. View details and make purchases.
- **Manage Wishlist:** Save and view your liked products.
- **Admin Dashboard:** Log in to manage users, view statistics, and handle products.

### Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.
 
### Contact
For any inquiries, feel free to reach out to me at houssemmhiri95@gmail.com.
