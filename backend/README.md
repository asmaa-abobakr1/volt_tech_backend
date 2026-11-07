Volt Tech – Backend

A RESTful backend application powering the Volt Tech e-commerce platform. Built with Node.js and Express.js, it handles application business logic, user authentication, database operations, product management, order processing, and image uploads.

🔗 Repository

Volt Tech Backend

🌐 API Base URL

https://grad-pro-backkkk.vercel.app/api

🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* JSON Web Token (JWT)
* bcrypt.js
* Multer
* Cloudinary

✨ Features

Authentication & Authorization

* User authentication.
* JWT-based authentication.
* Secure password hashing using bcrypt.js.
* Protected routes and authorization.

Product Management

* Product creation and management.
* Product data retrieval.
* Product information management.
* Product image upload and storage.

Order Management

* Order creation and processing.
* Order data management.
* Integration with the frontend shopping workflow.

Database Management

* MongoDB integration.
* Mongoose schemas and models.
* Structured data management.

Image Management

* Multer for handling file uploads.
* Cloudinary for cloud-based image storage.

🏗️ Architecture

The backend follows a modular architecture that separates application responsibilities into different layers:

* Models: Define database schemas and data structures.
* Controllers: Handle application logic and process requests.
* Routes: Define API endpoints.
* Middleware: Handle authentication and request processing.
* Configuration: Manage database and external service connections.

⚙️ Installation

Prerequisites

* Node.js
* npm
* MongoDB or MongoDB Atlas account
* Cloudinary account

Setup

git clone https://github.com/asmaa-abobakr1/volt_tech_backend.git
cd volt_tech_backend
npm install

Environment Variables

Create a .env file in the project root and configure the required variables:

PORT=5000
NODE_ENV=development
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

Adjust the variable names according to the actual backend configuration.

Run the Server

npm run dev

🔐 Security

* Password hashing with bcrypt.js.
* JWT-based authentication.
* Protected API endpoints.
* Environment variables for sensitive configuration.
* Middleware-based request handling.

🎯 Project Goals

* Develop scalable RESTful APIs.
* Implement secure authentication and authorization.
* Manage e-commerce data using MongoDB.
* Handle file uploads and cloud storage.
* Build a maintainable backend architecture.

👩‍💻 Developer

Asmaa Ahmed Abobakr

Full-Stack Developer | Node.js | Express.js | MongoDB