# MERN Auth App

This is a straightforward authentication app created using the MERN stack (MongoDB, Express, React, and Node.js). The application enables users to register, log in, and access a dashboard page. It implements JSON Web Tokens (JWT) and cookies for authentication, and utilizes bcrypt for password hashing.

## Features

- User registration and login with form validation
- Protected routes and dashboard page
- JWT and cookie-based authentication
- Password hashing with bcrypt
- Responsive design with Bootstrap

## Technologies

- MongoDB
- Express
- React
- Node.js
- JWT
- bcrypt
- Bootstrap

## Installation

To run this project locally, ensure that MongoDB, Node.js, and npm are installed on your machine.

1. Clone this repository or download the ZIP file.
2. Open the project folder in your preferred code editor.
3. In the root folder, create a file named `.env` and add the following variables:

   ```
   MONGO_URI = your MongoDB connection string
   JWT_SECRET = your JWT secret key
   ```

4. In the root folder, run `npm install` to install the backend dependencies.
5. In the root folder, run `npm run client-install` to install the frontend dependencies.
6. Run `npm run dev` in the root folder to start both the backend and frontend servers.
7. Open your browser and navigate to `http://localhost:3000` to view the app.

## Usage

To use the app, you can either register as a new user or log in with an existing user account. Two user accounts are already created for testing purposes:

- Email: john@example.com, Password: 123456
- Email: jane@example.com, Password: 123456

Once logged in, you can access the dashboard page, where you can view your user information and log out.
