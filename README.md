Blogify MERN Blogging Platform
A full-stack blogging platform built using the MERN (MongoDB, Express.js, React.js, Node.js) stack, designed for users to create, view, and manage blog posts with authentication and authorization features.

Features
User Authentication (Login/Register)
Blog Creation, Editing, and Deletion
View Blogs with Comment Support
Responsive UI using EJS and CSS
Getting Started
Prerequisites
Node.js (v14+ recommended)
MongoDB (local or Atlas)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/NP5555/Blogify_MERN-Blogging-platform.git
cd Blogify_MERN-Blogging-platform
Install dependencies for the server and client:

bash
Copy code
npm install
Set up environment variables:

Create a .env file in the root directory and add:
plaintext
Copy code
MONGO_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
PORT=<your-preferred-port>
Start the application:

bash
Copy code
npm start
Access the platform at http://localhost:<PORT>.

Folder Structure
/server: Backend API built with Express
/public: Static assets
/views: Frontend views in EJS
Contributing
Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.
