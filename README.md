# Task Management App

This project is a **Task Management App** built with **Node.js**, **Express**, and **MongoDB**. The app features a secure user authentication system, task management capabilities, and proper error handling, demonstrating robust backend development practices using the **MVC (Model-View-Controller) architecture**.

## 🚀 Features

- **User Authentication**: Register, login, and logout functionality with **JWT** and secure password hashing using **bcrypt**.
- **Task Management**: Users can create, update, and delete tasks. Task status can be toggled to indicate completion.
- **Error Handling**: Comprehensive error handling to manage various edge cases efficiently.
- **Cookies & Authentication**: Secure cookies to handle user sessions, compliant with development and production environments.
- **Database Integration**: Data persistence using **MongoDB** with **Mongoose**.
- **Environment Configuration**: Secure configuration management using **dotenv**.

## 🏛️ Architecture

The app follows the **MVC (Model-View-Controller) architecture**, which separates the application into three interconnected components:

- **Model**: Defines the data schema using Mongoose and handles database operations.
- **View**: Not applicable in this backend-focused project but could represent the response data in a full-stack setup.
- **Controller**: Manages the logic and interacts with the Model to process requests and send appropriate responses.

## 🛠️ Technologies Used

- **Backend Framework**: [Express.js](https://expressjs.com/)
- **Database**: [MongoDB](https://www.mongodb.com/)
- **Authentication**: [JWT](https://jwt.io/), [bcrypt](https://www.npmjs.com/package/bcrypt)
- **Environment Variables**: [dotenv](https://www.npmjs.com/package/dotenv)
- **HTTP Cookie Handling**: [cookie-parser](https://www.npmjs.com/package/cookie-parser)
- **Cross-Origin Resource Sharing**: [CORS](https://www.npmjs.com/package/cors)

## 📂 Project Structure

src │ ├── controllers # Controllers for handling business logic │ ├── task.js # Task controller logic │ └── user.js # User controller logic │ ├── middlewares # Middleware functions for authentication and error handling │ ├── auth.js # Authentication middleware │ └── error.js # Error handling middleware │ ├── models # Models for data schema and database interaction │ ├── task.js # Task schema and model │ └── user.js # User schema and model │ ├── routes # Routes for defining API endpoints │ ├── task.js # Task routes │ └── user.js # User routes │ ├── data # Database connection configuration │ └── database.js # Database connection │ ├── utils # Utility functions │ └── features.js # Utility functions (e.g., sending cookies) │ ├── app.js # Express app setup └── server.js # Server configuration and startup
