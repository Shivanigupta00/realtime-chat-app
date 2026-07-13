# 💬 Real-Time Messaging application

Built a scalable real-time messaging application using the MERN stack and Socket.IO, enabling bi-directional communication, secure JWT authentication, online/offline presence, image sharing with Cloudinary, and profile management.

## 🚀 Live Demo

🌐 **Link:** [https://shivani-socket-chat.vercel.app](https://shivani-socket-chat.vercel.app)

---

## ✨ Features

*   🔐 **JWT Authentication:** Secure signup and login flows.
*   💬 **Real-Time Messaging:** Instant message delivery powered by Socket.IO.
*   🟢 **User Status:** Live online/offline indicators for users.
*   🖼️ **Image Sharing:** Fast image uploads and media sharing via Cloudinary.
*   👤 **Profile Management:** Fully customizable user profiles.
*   🔒 **Protected Routes:** Route guards ensuring authenticated access only.
*   📱 **Responsive UI:** Seamless experience across mobile, tablet, and desktop devices.
*   ☁️ **Database:** Cloud-hosted data management with MongoDB Atlas.

---

## 🛠️ Tech Stack

### Frontend
*   **Core:** React.js, Vite
*   **Styling:** Tailwind CSS
*   **Networking & Real-time:** Axios, Socket.IO Client

### Backend
*   **Core:** Node.js, Express.js
*   **Database:** MongoDB Atlas, Mongoose
*   **Authentication & Security:** JWT, Bcrypt.js
*   **File Storage:** Cloudinary
*   **Real-time:** Socket.IO

---

## 📂 Project Structure

```text
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
└── server/
    ├── controllers/
    ├── middleware/
    ├── models/
    ├── routes/
    ├── lib/
    └── server.js
---
```
## ⚙️Environment Variables
Create a .env file in the respective directories and map the following keys:
**Server Environment Variables (/server/.env)**
```
PORT=5001
MONGODB_URI=
JWT_SECRET=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```
**Client Environment Variables (/client/.env)**
```
VITE_BACKEND_URL=
```
## 🖥️ Installation & Setup
Follow these steps to run the project locally:
1. **Clone the repository:**
   ```
   git clone [https://github.com/Shivanigupta00/realtime-chat-app.git](https://github.com/Shivanigupta00/realtime-chat-app.git)
   cd realtime-chat-app
   ```
2. **Setup and Run Backend:**
   ```
    cd server
    npm install
    node server.js
    ```
3. **Setup and Run Frontend:**
   ```
   cd ../client
    npm install
    npm run dev
    ```
## 🔒 Security
* 🔑 **Passwords are securely hashed using Bcrypt.js.**
* 🛡️ **Handled secure user sessions with JWT-based Authentication.**
* 🙈 **Sensitive credentials are strictly stored in .env configurations.**
* 🚫 **Environment variables are explicitly excluded from Git version control using .gitignore.**
   

 ## 👩‍💻 Author

**Shivani Gupta**

**GitHub:** [https://github.com/Shivanigupta00](https://github.com/Shivanigupta00)
