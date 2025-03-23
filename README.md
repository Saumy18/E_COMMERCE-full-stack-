# E_COMMERCE-full-stack-


## Overview
This is a full-stack e-commerce website built using modern web technologies. It provides a seamless shopping experience for users, featuring product listings, a shopping cart, user authentication, and an admin dashboard.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Backend:** JavaScript (Node.js, Express.js)
- **Database:** MongoDB
- **Deployment:** Vercel (Frontend), Backend (Hosted on a Cloud Platform or Local Server)

## Features
- User Authentication (Login/Signup)
- Product Catalog with Categories
- Shopping Cart.
- Admin Dashboard for Product Management
- Responsive Design
- Secure API Integration



### Prerequisites
Make sure you have the following installed:
- Node.js
- MongoDB

### Steps to Set Up the Project

2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     MONGO_URI=your_mongodb_connection_string
     PORT=5000
     ```
4. Start the backend server:
   ```bash
   node server.js
   ```
5. Navigate to the frontend directory and deploy it using Vercel:
   ```bash
   vercel
   ```

## Usage
- Open the frontend URL provided by Vercel.
- Register/Login to access the store.
- Browse products, add them to the cart, and proceed to checkout.
- Admins can add, edit, or delete products from the dashboard.

## Folder Structure
```
/ECOM_WEB
│── /api
│   ├── products.json
│── /node_modules
│── /public
│   ├── /Image
│   ├── vite.svg
│── /src
│   ├── addToCart.js
│   ├── fetchQuantityFromCartLS.js
│   ├── getCartProducts.js
│   ├── homeProductCards.js
│   ├── homeQuantityToggle.js
│   ├── incrementDecrement.js
│   ├── main.js
│   ├── removeProdFromCart.js
│   ├── showAddToCart.js
│   ├── showToast.js
│   ├── updateCartProductTotal.js
│   ├── updateCartValue.js
│   ├── style.css
│── .gitignore
│── about.html
```

## Deployment
- The frontend is deployed on **Vercel**.
- The backend can be hosted on a cloud platform such as Heroku, Render, or a dedicated server.


## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## Contact
For any queries, reach out to "SAUMY RAJ" at **22052674@kiit.ac.in**.

