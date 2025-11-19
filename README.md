Microservices-Based Blog Platform
A scalable blogging platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and designed with a microservices-oriented architecture for modular development, easier maintenance, and independent service deployment.

Features
User Authentication & Authorization — Secure login and signup using JWT.
Create, Read, Update, Delete (CRUD) blogs.
View Blogs from Other Users — Explore and read posts written by others.
Microservices Architecture — Separate services for users and blogs.
RESTful APIs for efficient communication between frontend and backend.
Timestamps to track creation and updates of blogs.
Responsive UI — Built with React for smooth and dynamic user experience.
Tech Stack
Layer	Technology
Frontend	React.js, Axios, React Router DOM
Backend	Node.js, Express.js
Database	MongoDB (Mongoose ODM)
Authentication	JWT (JSON Web Token)
Styling	CSS, React Components
Architecture	Microservices-based MERN Stack
Follow these steps to run the project on your local machine:

Clone the Repository

Navigate to the Project Folder

Install Dependencies For backend: cd server npm install For frontend: cd ../client npm install

Set Up Environment Variables Create a .env file inside the server folder and add:

MONGO_URI=mongodb://127.0.0.1:27017/BlogApp PORT=5000 JWT_SECRET=blogapp_secret

5️. Start the Servers Run backend:

cd server npm start

Run frontend: cd ../client npm start

6️. Open in Browser

Visit 👉 http://localhost:3000
