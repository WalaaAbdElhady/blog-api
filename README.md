# Blog API

Blog API can be used to manage posts and comments as well as go through the registration and logging user process using a JWT token.

## Features

- Authentication using JSON Web tokens (JWT) & Authorization
- Post CRUD operations
- Comment functionality
- Use error-handling middleware
- A user can follow and unfollow another user
- A user can close his account

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Nodemailer

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/WalaaAbdElhady/blog-api.git
   
2. Create a config.env file in the root of the project and add the following environment variables:
   
   ```env
   NODE_ENV=development
   PORT=3000
   DATABASE=your_mongodb_connection_string
   DATABASE_PASSWORD=your_mongodb_password
   
   JWT_SECRET=your_jwt_secret_key
   JWT_EXPIRES_IN=90d
   JWT_COOKIE_EXPIRES_IN=90

   EMAIL_USERNAME=your_email_username
   EMAIL_PASSWORD=your_email_password
   
   EMAIL_HOST=your_email_host
   EMAIL_PORT=your_email_port

4. Install dependencies:
   
   ```bash
   npm install
   
6. Run the application:
   
   ```bash
   npm run start:dev

