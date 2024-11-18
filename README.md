# e-commerce
e-commerce site selling sneakers(shoes)
# Sneakerzz

Welcome to Sneakerzz – where style meets comfort! Sneakerzz is an e-commerce platform dedicated to buying shoes, built on the MERN (MongoDB, Express.js, React.js, Node.js) stack. Sneakerzz not only provides a user-friendly interface for customers to browse and purchase shoes but also includes an admin section for managing products, orders, and users. Additionally, it features a secure payment section powered by Stripe.

## Technologies Used

- **React.js**: Frontend library for building the user interface.
- **Node.js**: JavaScript runtime environment for running server-side code.
- **Express.js**: Backend framework for handling HTTP requests and routing.
- **MongoDB**: Database for storing products, user information, and orders.
- **JWT (JSON Web Tokens)**: Used for user authentication and authorization.
- **Axios**: Promise-based HTTP client for making AJAX requests from the frontend to the backend.
- **Stripe**: Payment processing platform for securely accepting payments online.

## Installation

Follow these steps to set up Sneakerzz on your local machine:

1.  **Clone the Repository:**

2.  **Install Dependencies:**

    Navigate to the client directory and install frontend dependencies:

    ```bash
    cd client
    npm install
    ```

    Next, open a new terminal tab, navigate to the server directory and install backend dependencies:

    ```bash
    cd server
    npm install
    ```

3.  **Set up Environment Variables:**

    Create a `.env` file in both the client and server directories and define the following variables in the `.env` file:

    **For Client:**

    ```plaintext
    VITE_REACT_APP_REMOVEBG_KEY=your_removebg_key
    VITE_BACKEND_URL=http://localhost:5000
    ```

    **For Server:**

    ```plaintext
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key
    STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
    CLIENT_URL=http://localhost:5173
    ```

4.  **Run the Backend Server:**

    Navigate to the server directory and run:

    ```bash
    nodemon app.js
    ```

5.  **Run the Frontend Server:**

    Navigate to the client directory and run:

    ```bash
    npm run dev
    ```

    After running this command, the project will start running locally at http://localhost:5173
