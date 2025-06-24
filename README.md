# Real-Time Chat App with Socket.IO

A full-stack real-time chat application built with **Node.js**, **Express**, **React**, **Socket.IO**, and **MongoDB**. It supports public chat rooms, private one-on-one conversations, typing indicators, online status updates, and persistent chat history.

## Live Demo

[Try the app now](https://chat-app-3gek.vercel.app/)

## Tech Stack

- **Frontend**: React.js, Tailwind CSS, Socket.IO-client
- **Backend**: Node.js, Express.js, Socket.IO, JWT
- **Database**: MongoDB (Mongoose)
- **Authentication**: JSON Web Tokens (JWT)
- 
## Features

✅ Real-time public and private chat  
✅ User authentication with JWT  
✅ Persistent chat history (MongoDB)  
✅ Typing indicators  
✅ Online/offline status tracking  
✅ Responsive UI with Tailwind CSS

## Chat-app folder structure

📦chat-app
┣ 📂client # React frontend
┃ ┣ 📂components # Chat UI components
┃ ┣ 📂pages # Login, Register, Chat pages
┃ ┗ 📜App.jsx # Root app file
┣ 📂server # Node.js backend
┃ ┣ 📂routes # Auth and chat routes
┃ ┣ 📂models # Mongoose schemas
┃ ┗ 📜socket.js # Socket.IO server logic
┣ 📜.env # Environment variables
┣ 📜package.json
