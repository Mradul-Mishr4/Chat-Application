# 🚀 ProChat - Professional Real-Time Chat Application

A modern, full-stack chat application built with React.js and Node.js, featuring real-time messaging capabilities powered by Socket.IO. Designed for professional team communication with a sleek, responsive interface.

![ProChat Demo](https://img.shields.io/badge/Status-Live-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Node](https://img.shields.io/badge/Node.js-v16+-green)
![React](https://img.shields.io/badge/React-16.9.0-blue)

## ✨ Features

- 💬 **Real-time messaging** with Socket.IO
- 🏢 **Room-based chat** for organized conversations
- 👥 **Multi-user support** with live user list
- 📱 **Responsive design** for mobile and desktop
- 🎨 **Professional UI/UX** with modern gradient themes
- 🔒 **Secure communication** with CORS protection
- ⚡ **Instant notifications** for user join/leave events
- 🌐 **Cross-platform compatibility**

## 🛠️ Tech Stack

### Frontend
- **React.js** (16.9.0) - User interface
- **React Router** - Client-side routing
- **Socket.IO Client** - Real-time communication
- **CSS3** - Modern styling with gradients and animations

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **Socket.IO** - Real-time bidirectional communication
- **CORS** - Cross-origin resource sharing

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/prochat.git
   cd prochat
   ```

2. **Install server dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies**
   ```bash
   cd ../client
   npm install
   ```

4. **Start the server**
   ```bash
   cd ../server
   npm start
   ```
   Server will run on `http://localhost:3333`

5. **Start the client**
   ```bash
   cd ../client
   NODE_OPTIONS="--openssl-legacy-provider" npm start
   ```
   Client will run on `http://localhost:3000`

## 📖 Usage

1. **Join a Conference**: Enter your display name and conference room ID
2. **Start Chatting**: Send real-time messages to other participants
3. **View Participants**: See who's currently active in the room
4. **Leave/Join Notifications**: Get notified when users join or leave

## 🏗️ Project Structure

```
prochat/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # React components
│   │   │   ├── Chat/       # Main chat interface
│   │   │   ├── InfoBar/    # Room info and participants
│   │   │   ├── Input/      # Message input component
│   │   │   ├── Join/       # Landing page
│   │   │   └── Messages/   # Message display
│   │   └── App.js          # Main application
│   └── package.json
├── server/                 # Node.js backend
│   ├── index.js           # Server entry point
│   ├── router.js          # Express routes
│   ├── users.js           # User management
│   └── package.json
└── README.md
```

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the server directory:
```env
PORT=3333
NODE_ENV=development
```

### Client Configuration
Update the endpoint in `client/src/components/Chat/Chat.js`:
```javascript
const ENDPOINT = 'http://localhost:3333';
```

## 🌐 Deployment

### Heroku Deployment
1. Create a Heroku app
2. Set buildpacks for both Node.js client and server
3. Configure environment variables
4. Deploy using Git

### Netlify + Railway
- Deploy client to Netlify
- Deploy server to Railway
- Update client endpoint configuration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔮 Future Enhancements

- [ ] File sharing capabilities
- [ ] Voice/Video calling integration
- [ ] Message encryption
- [ ] User authentication
- [ ] Message history persistence
- [ ] Emoji reactions
- [ ] Typing indicators
- [ ] Dark/Light theme toggle

## 📞 Support

If you have any questions or need help getting started, please open an issue or contact the maintainers.

---

**⭐ Star this repository if you found it helpful!**
