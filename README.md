# Blog App using MERN Stack

## Overview

This is a full-stack Blog application built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to create, read, update, and delete blog posts, and also includes user authentication.


## Features

- User Registration and Authentication
- Create, Read, Update, and Delete blog posts
- User-friendly and responsive user interface
- API endpoints for managing posts and users
- MongoDB for database storage

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd blog-app
   ```

3. Install server dependencies:

   ```bash
   cd server
   npm install
   ```

4. Install client dependencies:

   ```bash
   cd client
   npm install
   ```

5. Set up environment variables:
   - Create a `.env` file in the `server` directory and add your MongoDB connection string and any other environment variables.

6. Start the server:

   ```bash
   cd server
   npm start
   ```

7. Start the client:

   ```bash
   cd client
   npm start
   ```

8. Open your browser and access the application at `http://localhost:3000`.

## Usage

- Register a new user or login with an existing account.
- Create, update, or delete blog posts.
- View and comment on existing blog posts.
- Explore the features of the application.

## Technologies Used

- **MongoDB** - NoSQL database for storing user information and blog posts.
- **Express.js** - Backend server framework for routing and API endpoints.
- **React** - Frontend library for building the user interface.
- **Node.js** - JavaScript runtime for the server.
- **Mongoose** - ODM (Object Data Modeling) library for MongoDB.
- **Passport.js** - Authentication middleware for user authentication.
- **Axios** - HTTP client for making API requests.
- **Material-UI** - UI framework for designing the user interface.

## File Structure

- `client/` - React frontend application.
- `server/` - Node.js server with Express.
- `server/routes` - Express routes for handling API requests.
- `server/models` - Mongoose models for defining data schema.
- `server/config` - Configuration files and environment variables.
- `server/controllers` - Controllers for handling business logic.
- `client/src` - React application source code.

## Contributing

Feel free to contribute to this project. You can open issues, create pull requests, or suggest improvements. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE).

---

