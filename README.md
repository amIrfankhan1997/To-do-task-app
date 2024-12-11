# ToDo Application

## Features

### Frontend

- User registration and login.
- Task creation, editing, and deletion.
- Real-time task completion toggle.
- Responsive UI.

### Backend

- User authentication using JWT.
- CRUD operations for tasks.
- RESTful API endpoints.
- Validation and error handling.

---

## Tech Stack

### Frontend

- React.js
- Axios
- React Router DOM

### Backend

- Node.js
- Express.js
- MongoDB with Mongoose

### Prerequisites

- Node.js and npm installed.
- MongoDB instance running locally or via a cloud provider.

### Steps

1. Navigate to the backend directory:
   cd backend

2. Install the required dependencies:
   npm init-y
   npm install

3. Create a .env file in the backend root directory and replace the following environment variables:

   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   PORT=5000

4. Start the backend serve:
   npm start

-> The backend server will be running at http://localhost:5000

# Frontend Setup for ToDo Application

## Installation and Setup

### Prerequisites

- Node.js and npm installed.

### Steps

1. Navigate to the frontend directory:
   cd frontend

2. Install the required dependencies:
   npm init-y
   npm start

3. Start the React development server:
   npm start

-> The frontend application will be running at http://localhost:3000 by default.

