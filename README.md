#  Full Stack Realtime Chat App 

![Demo App](/frontend/public/screenshot-for-readme.png)

# Chat App (MERN Stack)

A real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js). Users can sign up, create profiles, chat one-on-one, share text messages and photos, and set custom profile pictures. The app uses **Cloudinary** for image hosting, **Socket.io** for real-time messaging, and **Zustand** for state management in React.

---

##  Features

- User registration and login (authentication)
- Real-time one-to-one chat using **Socket.io**
- Send and receive text messages
- Share photos in chat
- Upload and set a profile picture
- User profiles with display name and photo
- Cloud image storage via **Cloudinary**
- Modern React frontend with **Zustand** for global state

---

##  Tech Stack

### Frontend
- React.js
- Zustand (state management)
- Axios
- Socket.io-client

### Backend
- Node.js
- Express
- MongoDB (with Mongoose)
- Socket.io
- Cloudinary SDK
- bcrypt / JWT (for auth)

---


---

##  Folder Structure Example
project-root/
│
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ ├── server.js
│ └── .env
│
└── frontend/
├── src/
│ ├── components/
│ ├── pages/
│ ├── store/
│ ├── App.js
│ └── index.js
└── .env

yaml
Copy
Edit

---

##  How It Works

1️⃣ **User Registration/Login**  
- Users create accounts with email/password.  
- JWT tokens are issued for authentication.  

2️⃣ **Profile Management**  
- Users can upload a profile picture (stored in Cloudinary).  
- Display name and photo shown in chats.

3️⃣ **Chat**  
- Users can search/select other users to chat with.  
- Real-time messaging powered by Socket.io.  
- Supports text and image messages.  
- Images are uploaded to Cloudinary and shared as links.

4️⃣ **State Management**  
- Zustand manages logged-in user state and chat state globally in the React app.

---

##  Installation

### Prerequisites
- Node.js
- npm
- MongoDB Atlas or local MongoDB

---

#
