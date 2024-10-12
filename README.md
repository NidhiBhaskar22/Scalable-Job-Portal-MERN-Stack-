# Scalable Job Portal

A scalable job portal built with the MERN stack, featuring user role management, JWT authentication for secure access, and Multer for file uploads. It utilizes RESTful APIs for seamless data flow between the frontend and backend, demonstrating my ability to develop secure, real-world applications.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
  

## Features
- **User Role Management**: Supports different user roles, including Admin, Recruiter, and Applicant, each with specific access rights.
- **JWT Authentication**: Implements secure user authentication using JSON Web Tokens, ensuring secure access to protected routes.
- **File Uploads**: Utilizes Multer to handle file uploads, such as resumes and other documents.
- **RESTful APIs**: Efficiently manages data flow and interactions between the frontend and backend, ensuring smooth user experiences.
- **Responsive Design**: User-friendly interface compatible with desktop and mobile devices.

## Technologies Used
- **Frontend**: 
  - React
  - Redux (if applicable)
  - Axios
- **Backend**: 
  - Node.js
  - Express.js
- **Database**: 
  - MongoDB
- **Authentication**: 
  - JSON Web Tokens (JWT)
- **File Uploads**: 
  - Multer
- **Version Control**: 
  - Git

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/NidhiBhaskar22/Scalable-Job-Portal-MERN-Stack.git
   cd Scalable-Job-Portal-MERN-Stack
Install dependencies for the backend:
cd server
npm install

Install dependencies for the frontend:
cd ../client
npm install

Set up environment variables:
Create a .env file in the server directory and add your MongoDB connection string and JWT secret. 

MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Run the application:

Start the backend server:
cd server
npm start

Start the frontend:
cd ../client
npm start

##Usage
Visit http://localhost:3000 in your browser to access the job portal.
Register or log in to start using the features.

#API Endpoints
POST /api/auth/register: Register a new user.
POST /api/auth/login: Authenticate user and return JWT.
GET /api/jobs: Fetch all job listings.
POST /api/jobs: Create a new job listing (Admin/Recruiter access).
GET /api/users: Fetch user details (Admin access).
For more detailed API documentation, please refer to the API documentation section.



### Instructions
- Replace `your-email@example.com` with your actual email.
- Ensure to create a **LICENSE** file in your repository if you mention it.
- Add more details or sections as needed, such as screenshots or examples of usage.

Feel free to let me know if you need further adjustments or additions!
