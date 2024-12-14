# User Authentication and Authorization with Bearer Token

## Project Description

This project implements user authentication and authorization in a Node.js application using Express.js, Mongoose, and JSON Web Tokens (JWT). The application follows the MVC (Model-View-Controller) design pattern and includes user registration, login, and profile access functionality protected with JWT tokens.

## Tech Stack

- **Node.js**: JavaScript runtime for building the server.
- **Express.js**: Web framework for building the API.
- **MongoDB**: NoSQL database for storing user data.
- **Mongoose**: ODM (Object Data Modeling) for MongoDB.
- **JWT (JSON Web Tokens)**: For secure authentication and authorization.
- **bcryptjs**: For hashing passwords.
- **Postman**: For API testing and documentation.

## Features

- **User Registration**: Register new users with a unique email and password.
- **User Login**: Authenticate users by validating credentials and generate a JWT token.
- **Protected Routes**: Access protected user profile route by sending a valid JWT in the Authorization header.
- **Password Hashing**: Securely store passwords using bcryptjs.
- **Error Handling**: Proper error handling and validation for different scenarios.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/auth-jwt-nodejs.git
cd auth-jwt-nodejs

```
## To Start your Sever
npm start

# Api EndPoints
- `https://auth-task-iy53.onrender.com/api/auth/register` : for register 
- `https://auth-task-iy53.onrender.com/api/auth/login` : for Login 
- `https://auth-task-iy53.onrender.com/api/auth/profile` : but if you want the profile you have to give the  HEADER - Authorization :  **Bearer** Token in POSTMAN 








