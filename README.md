# 💬 Real-Time Chat App
 
A modern, real-time messaging application built with **Node.js**, **Socket.IO**, and **React**. Features instant messaging, user authentication, and responsive design.

## ✨ Features

- 💬 **Real-time messaging** with instant delivery
- 👥 **User authentication** and profiles
- 🏠 **Multiple chat rooms** and private messaging
- 📱 **Responsive design** for all devices
- 🎨 **Dark/Light theme** support
- 📎 **File sharing** and image uploads

## 🛠️ Installation

### Prerequisites
- Node.js (v16+)
- MongoDB
- npm or yarn

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/kshitij1730/chatting-app.git
   cd real-time-chat-app
   ```

2. **Install dependencies**
   ```bash
   # Backend
   cd server && npm install
   
   # Frontend
   cd client && npm install
   ```

3. **Environment variables**
   Create `.env` file in root:
   ```env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/chatapp
   JWT_SECRET=your-jwt-secret
   ```

4. **Start the application**
   ```bash
   # Development mode (from root)
   npm run dev
   
   # Or start separately
   cd server && npm run dev
   cd client && npm start
   ```

5. **Access the app**
   - Frontend: http://localhost:3000
   - Backend: http://localhost:5000

## 🚀 Technologies Used

- **Frontend:** React, Socket.IO Client, Material-UI
- **Backend:** Node.js, Express, Socket.IO, MongoDB
- **Authentication:** JWT
- **Real-time:** WebSockets

## 🤝 Contributing

1. Fork the project
2. Create feature branch (`git checkout -b feature/NewFeature`)
3. Commit changes (`git commit -m 'Add NewFeature'`)
4. Push to branch (`git push origin feature/NewFeature`)
5. Open Pull Request

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

<div align="center">
Made with ❤️ using React & Node.js
</div>
