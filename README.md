# 🛠 Twitter Clone – MERN Stack

A full-stack Twitter Clone built using React.js, Node.js, Express.js, and MongoDB, featuring authentication, post creation, liking, commenting, and profile management.

## 📌 Project Description: Twitter Clone (MERN Stack)

This project is a fully functional Twitter Clone built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). It replicates key features of Twitter, including user authentication, post creation, likes, comments, profile management, and real-time notifications.
The project was developed as a learning and side project to enhance my full-stack development skills. I followed this [YouTube tutorial](https://www.youtube.com/watch?v=4GUVz2psWUg) as a foundation but introduced several optimizations, including improved API performance, state management with React Query, and UI enhancements with TailwindCSS and DaisyUI.
It serves as a great reference for anyone looking to understand modern web development with React, Node.js, MongoDB, and cloud deployment.

## 🚀 Getting Started
This guide will walk you through setting up the Twitter Clone project on your local machine for development and testing. Follow the steps below to get started.
📌 Prerequisites
Before running the project, ensure you have the following installed:
✅ Node.js (v16 or later)
✅ MongoDB (for local database setup or MongoDB Atlas)
✅ Git (for cloning the repository)
✅ A package manager (either npm or yarn)

### 📦 Dependencies

🔹 Backend Dependencies (Node.js & Express)
  - express – Web framework for Node.js
  - mongoose – ODM for MongoDB
  - jsonwebtoken – Secure authentication with JWT
  - bcryptjs – Password hashing
  - dotenv – Environment variable management
  - cors – Cross-Origin Resource Sharing
  - cookie-parser – Parse HTTP cookies
  - cloudinary – Image storage & management
    
🔹 Frontend Dependencies (React)
  - react-router-dom – Client-side routing
  - react-icons – Icons for UI
  - @tanstack/react-query – Optimized API fetching & caching
  - tailwindcss – Utility-first CSS framework
  - daisyui – Prebuilt UI components
    
🔹 Dev Dependencies
  - nodemon – Automatically restarts the server on code changes

### ⚡ Installation & Setup
1. Clone the Repository
   ```
   git clone https://github.com/Avaneeshakrishna/TwitterClone.git
   cd TwitterClone
   ```

2. Backend Setup (Node.js & Express)
   ```
   cd backend
   npm init -y                            #Initialize Node.js project (if not already done)
   npm install express mongoose jsonwebtoken bcryptjs dotenv cors cookie-parser cloudinary #Install dependencies
   npm i -D nodemon                       # Install nodemon (for development)
   npm run dev                            # Start the backend server
   ```
  MongoDB Setup (Local or Atlas)
   - If using MongoDB Atlas, update MONGO_URI in your .env file.
   - If using local MongoDB, ensure your MongoDB service is running.

  Create a JWT Secret Key
  - Run the following command in Git Bash:
    ```
    openssl rand -base64 32
    ```
Copy the generated key and add it to your .env file: (It may look like this)\
JWT_SECRET=your_generated_secret\
MONGO_URI=your_mongodb_connection_string\
CLOUDINARY_CLOUD_NAME=your_cloudinary_name\
CLOUDINARY_API_KEY=your_api_key\
CLOUDINARY_API_SECRET=your_api_secret\

3. Frontend Setup (React & Vite)
5. 

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
