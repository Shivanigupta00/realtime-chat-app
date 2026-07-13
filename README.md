💬 Real-Time Chat Application

A full-stack real-time chat application built using the MERN stack and Socket.IO. It enables users to communicate instantly with secure JWT authentication, image sharing through Cloudinary, and a responsive user interface.

🚀 Live Demo

🌐 https://shivani-socket-chat.vercel.app

✨ Features
🔐 JWT Authentication (Signup & Login)
💬 Real-Time Messaging using Socket.IO
🟢 Online/Offline User Status
🖼️ Image Sharing with Cloudinary
👤 User Profile Management
🔒 Protected Routes
📱 Responsive UI
☁️ MongoDB Atlas Database
🛠️ Tech Stack
Frontend
React.js
Vite
Tailwind CSS
DaisyUI
Zustand
Axios
Socket.IO Client
Backend
Node.js
Express.js
MongoDB Atlas
Mongoose
Socket.IO
JWT
Bcrypt.js
Cloudinary
📂 Project Structure
realtime-chat-app/
│
├── client/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── lib/
│   │   ├── App.jsx
│   │   └── main.jsx
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── lib/
│   └── server.js
⚙️ Environment Variables
Server
PORT=

MONGODB_URI=

JWT_SECRET=

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=
Client
VITE_BACKEND_URL=
🖥️ Installation
git clone https://github.com/Shivanigupta00/realtime-chat-app.git

cd realtime-chat-app

# Backend
cd server
npm install
npm run dev

# Frontend
cd ../client
npm install
npm run dev
🔒 Security
Passwords hashed using Bcrypt
JWT-based Authentication
Sensitive credentials stored in .env
Environment variables excluded from Git using .gitignore
🚀 Future Enhancements
Group Chat
Typing Indicator
Read Receipts
Push Notifications
Emoji Support
Voice Messages
Video Calling
Message Search
👩‍💻 Author

Shivani Gupta

GitHub: https://github.com/Shivanigupta00
