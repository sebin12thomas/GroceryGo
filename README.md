

```markdown
# Grocery Go - Local Setup Guide

Welcome to Grocery Go! This guide will walk you through the steps to initialize and run the project on your local machine.

## Prerequisites

Before getting started, make sure you have the following installed on your system:

- Node.js (https://nodejs.org/)
- MongoDB (https://www.mongodb.com/)

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your_username/grocery-go.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd grocery-go
   ```

3. **Install Dependencies:**

   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

4. **Set Up Environment Variables:**

   - Create a `.env` file in the `backend` directory.
   - Add the following environment variables to the `.env` file:

     ```plaintext
     PORT=3000
     MONGODB_URI=your_mongodb_uri
     ```

5. **Seed the Database:**

   ```bash
   # In the backend directory
   npm run seed
   ```

6. **Start the Backend Server:**

   ```bash
   # In the backend directory
   npm start
   ```

7. **Start the Frontend Server:**

   ```bash
   # In the frontend directory
   npm start
   ```

8. **Access the Application:**

   Open your web browser and navigate to `http://localhost:3000` to access Grocery Go.

## Additional Notes

- The default port for the backend server is 3000. Make sure this port is available and not used by any other application.
- Replace `your_mongodb_uri` in the `.env` file with your MongoDB connection URI.
- You can customize other environment variables in the `.env` file as needed.

Happy shopping with Grocery Go!
```
