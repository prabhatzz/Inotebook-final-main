# Inotebook - MERN Stack Project

## Introduction

Welcome to Inotebook! This project is an online web platform designed to help you create, edit, upload, and delete your notes and information securely and privately. Built using the MERN stack (MongoDB, Express.js, React.js, and Node.js), Inotebook ensures the security of your data with JWT authentication and bcrypt.js for password encryption.

## Demo Video
[![Watch the video](https://img.youtube.com/vi/Jt2Lo3PXlEA/maxresdefault.jpg)](https://youtu.be/Jt2Lo3PXlEA)


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [Contributing](#contributing)


## Features

- User authentication (Sign up, Log in, Log out)
- Create, edit, and delete notes
- Secure storage with JWT authentication
- Password encryption using bcrypt.js
- Responsive design

## Technologies Used

- **Frontend:**
  - React.js
  - Redux for state management
  - Bootstrap for styling

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB

- **Security:**
  - JSON Web Tokens (JWT)
  - bcrypt.js for password hashing

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Andriyas05/Inotebook-final.git
   cd Inotebook-final
   ```

2. **Install dependencies for both frontend and backend:**
   ```bash
   # For frontend
   npm install
   

   
   # For backend
   cd backend
   npm install

   ```

   

## Configuration

### Backend Configuration

1. Create a `.env` file in the `backend` directory and add the following environment variables:
   ```plaintext
   PORT=5000
   MONGODB_URL=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret_key>
   ```

### Frontend Configuration

1. Create a `.env` file in the `frontend` directory and add the following environment variables:
   ```plaintext
   REACT_APP_API_URL=http://localhost:5000/api
   ```

## Running the Application

1. **Start the backend server:**
   ```bash
   cd backend
   npm start
   ```

2. **Start the frontend development server:**
   ```bash
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to view the application.


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes.
4. Submit a pull request with a detailed description of your changes.






### Project Images
Home Page
<img src="./project images/home.png" alt="Logo" >

All Notes
<img src="./project images/all notes.png" alt="Logo" >

New Note
<img src="./project images/new Note.png" alt="Logo" >

edit Note
<img src="./project images/edit Note.png" alt="Logo" >

Login Page
<img src="./project images/login.png" alt="Logo">

Register Page
<img src="./project images/register.png" alt="Logo">

About Page
<img src="./project images/about.png" alt="Logo">
<img src="./project images/about1.png" alt="Logo">

404 Page
<img src="./project images/404 page.png" alt="Logo">

<p align="right">(<a href="#top">back to top</a>)</p>


---

Thank you for checking out Inotebook. If you have any questions or feedback, please feel free to open an issue or reach out to the maintainers. Happy coding!



