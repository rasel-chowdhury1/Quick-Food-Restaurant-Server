### Quick Food Restaurant - Server-side Code

This repository contains the server-side code for the Quick Food Restaurant Management System. Below, you will find a summary of the key functionalities and APIs implemented in this server.

---

### Key Features

1. **JWT Authentication and Authorization**
   - Secure user authentication using JSON Web Tokens (JWT).
   - Role-based authorization to restrict access to certain endpoints.

2. **Database Integration**
   - MongoDB integration for storing user data, menu items, reviews, bookings, payments, and messages.

3. **API Endpoints**
   - User management APIs for registration, login, and profile management.
   - Admin-specific APIs for managing users, menu items, and accessing statistics.
   - APIs for managing cart items, reviews, bookings, payments, and sending emails.

4. **Payment Integration**
   - Integration with Stripe for processing secure payments.

5. **Middleware**
   - CORS middleware to enable cross-origin resource sharing.
   - Custom middleware for verifying JWT tokens and user roles.

### Technologies Used

- Express.js: Node.js web application framework for building APIs.
- MongoDB: NoSQL database for storing application data.
- JWT: JSON Web Tokens for secure user authentication.
- Stripe: Payment processing platform for handling transactions.
- Nodemailer: Module for sending emails.
- CORS: Middleware for enabling cross-origin resource sharing.
