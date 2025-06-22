Chat App

A real-time chat application that allows users to communicate instantly through text messages, with support for image/file uploads. This project is built with a modern tech stack to provide a seamless and interactive user experience.
Features

Real-Time Messaging: Send and receive messages instantly using WebSocket technology.
User Authentication: Secure login and registration system powered by Clerk.
Private and Group Chats: Support for one-on-one and group conversations .
Image/File Uploads: Upload images or files via Cloudinary integration.
Responsive Design: Works on desktops, tablets, and mobile devices.
Message History: Persists chat history for users.

Tech Stack

Frontend: React, Tailwind CSS
State Management: Zustand
Backend: Node.js, Express.js
Real-Time Communication: Socket.IO
Database: MongoDB
Authentication: Clerk
File Storage: Cloudinary

Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v16 or higher recommended)
npm or yarn
MongoDB Atlas account or a local MongoDB instance
A Clerk account for authentication setup
A Cloudinary account for file uploads
A code editor like VS Code

Installation

Clone the repository:
git clone https://github.com/rawanatef634/chat-app.git
cd chat-app


Install dependencies:For the backend (if in a separate folder, e.g., /server):
cd server
npm install

For the frontend (if in a separate folder, e.g., /client):
cd client
npm install @clerk/clerk-react zustand cloudinary


Set up environment variables:Create a .env file in the server directory and add the following:
PORT=5001
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
NODE_ENV=production

Create a .env.local file in the client directory and add Clerk keys:
REACT_APP_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

Obtain your MongoDB URI from MongoDB Atlas, Clerk keys from the Clerk Dashboard, and Cloudinary credentials from the Cloudinary Dashboard.

Run the application:

Start the backend server:cd server
npm start


Start the frontend development server:cd client
npm start


Open your browser and navigate to http://localhost:3000.



Usage

Register/Login: Use Clerk's authentication interface to sign up or log in.
Start Chatting: Select a user or group to begin sending messages, with state managed by Zustand for a smooth experience.
Upload Files: Share images or files using the Cloudinary-powered upload feature.
Explore Features: Try out real-time messaging, emojis, or other implemented features.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.

Please follow the Code of Conduct and ensure your code adheres to the project's style guidelines.
License
This project is licensed under the MIT License.
Contact
For questions or feedback, reach out to Rawan Atef or open an issue on this repository.

Built with 💬 by Rawan Atef
