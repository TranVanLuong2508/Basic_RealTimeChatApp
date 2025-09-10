# 💬 Realtime Chat Application

A real-time chat application built with React.js and Node.js, featuring instant messaging, image sharing, and online user status tracking.

## Demo

**🌐 Live Demo:** [Click here to try the app](https://basic-realtimechatapp.onrender.com/)

## Development Repositories (Original Source Code)
- **Frontend (React.js):** [Frontend](https://github.com/TranVanLuong2508/Chatty-Frontend)
- **Backend (Node.js):** [Backend](https://github.com/TranVanLuong2508/Chatty-Backend)


### 🔐 Demo Accounts for Testing

| Username | Password |
|----------|----------|
| emma.thompson@example.com | 123456 |
| olivia.miller@example.com | 123456 |

*Note: You can register a new account or use the demo accounts above to experience the application.*

## Features

- **Real-time Chat** - Instant messaging with Socket.IO
- **Image Sharing** - Share images in conversations
- **Online Status** - Track online/offline user status
- **Theme Customization** - Change themes with DaisyUI
- **Profile Management** - View and edit personal information
- **JWT Authentication** - Secure authentication with JSON Web Token and cookies
- **Responsive Design** - Compatible with all devices

## Tech Stack

### Frontend
- **React.js** - JavaScript library for building user interfaces
- **DaisyUI** - Component library based on Tailwind CSS
- **Socket.IO Client** - Real-time communication with server
- **Zustand** - Global state management
- **Tailwind CSS** - Utility-first CSS framework

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **Socket.IO** - Real-time bidirectional communication library
- **JWT** - JSON Web Token for authentication
- **Cookie Parser** - Cookie handling middleware

## Installation Guide

### System Requirements
- Node.js >= 14.0.0
- npm or yarn

### Local Setup and Installation

1. **Clone repository**
   ```bash
   git clone https://github.com/TranVanLuong2508/Basic_RealTimeChatApp.git
   cd Basic_RealTimeChatApp
   ```

2. **Install server dependencies**
   ```bash
   cd Backend
   npm install
   ```

3. **Install client dependencies**
   ```bash
   cd ../Fronted
   npm install
   ```

4. **Configure environment variables**
   
   Create `.env` file in `Backend/` directory:
   ```env
   MONGODB_URI=[your URI]
   
   PORT=[your-Backend-port]
   
   JWT_SECRET=[your-secret]
   
   
   REACT_URL=[your-Frontend-URL]
   
   CLOUDINARY_CLOUD_NAME=dpfbad8fi
   CLOUDINARY_API_KEY=[your-cloudinary-key]
   CLOUDINARY_API_SECRET=[your-cloudinary-secret-API]
   
   NODE_ENV=development
   ```

5. **Run the application**

   Terminal 1 - Run server:
   ```bash
   cd Backend
   npm run dev
   ```

   Terminal 2 - Run client:
   ```bash
   cd Frontend
   npm run dev
   ```

6. **Access the application**
   - Frontend: http://localhost:[your-Backend-port]
   - Backend API: http://localhost:[your-Frontend-port]

## Theme Customization

The application supports multiple DaisyUI themes:
- Light
- Dark
- Cupcake
- Bumblebee
- Emerald
- Corporate
- Synthwave
- Retro
- Cyberpunk
- Valentine
- Halloween
- Garden
- Forest
- Aqua
- Lofi
- Pastel
- Fantasy
- Wireframe
- Black
- Luxury
- Dracula

Change themes in the application Settings section.

## Detailed Features

### Real-time Chat
- Send and receive instant messages
- Store chat history

### Image Sharing
- Upload and share images
- Preview images before sending
- Display thumbnails in chat

### User Management
- User registration/login
- View other users' profiles
- Update avatar and personal information

### Security
- JWT authentication
- Store tokens in httpOnly cookies
- Middleware protection for routes
