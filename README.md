# Collaborate-x 🚀

A real-time collaborative code editor and drawing platform built with React, TypeScript, and Socket.IO. Collaborate with team members in real-time with features like live code editing, drawing collaboration, file management, and chat functionality.

## ✨ Features

### 🎯 Core Features
- **Real-time Code Collaboration**: Multiple users can edit code simultaneously with live synchronization
- **Multi-language Support**: Syntax highlighting for various programming languages using CodeMirror
- **Drawing Collaboration**: Real-time drawing and sketching with TLDraw integration
- **File Management**: Create, edit, rename, and organize files in a collaborative workspace
- **Live Chat**: Built-in chat system for team communication
- **User Presence**: See who's online and their current activities
- **Room-based Collaboration**: Join specific rooms for focused collaboration

### 🛠️ Technical Features
- **Real-time Synchronization**: Instant updates across all connected users
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI/UX**: Clean, intuitive interface built with Tailwind CSS
- **TypeScript**: Full type safety throughout the application
- **Socket.IO**: Real-time bidirectional communication
- **CodeMirror**: Advanced code editing with syntax highlighting
- **File Export**: Download project files as ZIP archives

## 🏗️ Tech Stack

### Frontend
- **React 18** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Styling
- **React Router** - Client-side routing
- **Socket.IO Client** - Real-time communication
- **CodeMirror** - Code editor
- **TLDraw** - Drawing functionality
- **React Hot Toast** - Notifications
- **React Split** - Resizable panels

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **Socket.IO** - Real-time communication
- **TypeScript** - Type safety
- **CORS** - Cross-origin resource sharing


## 📖 Usage

### Creating a Collaboration Session
1. Open the application in your browser
2. Enter your username and room ID
3. Click "Join Room" to start collaborating

### Joining an Existing Session
1. Enter the same room ID as your collaborators
2. Choose a unique username
3. Click "Join Room" to join the session

### Features in the Editor
- **Code Editing**: Write and edit code with real-time collaboration
- **File Management**: Create, rename, and organize files
- **Drawing**: Use the drawing tool for diagrams and sketches
- **Chat**: Communicate with team members
- **User List**: See who's currently in the room
- **Settings**: Customize your experience

## 📁 Project Structure

```
Collaborate-x/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # React components
│   │   │   ├── chats/      # Chat-related components
│   │   │   ├── drawing/    # Drawing functionality
│   │   │   ├── editor/     # Code editor components
│   │   │   ├── files/      # File management
│   │   │   ├── sidebar/    # Sidebar components
│   │   │   └── workspace/  # Main workspace
│   │   ├── context/        # React context providers
│   │   ├── hooks/          # Custom React hooks
│   │   ├── pages/          # Page components
│   │   ├── types/          # TypeScript type definitions
│   │   └── utils/          # Utility functions
│   ├── public/             # Static assets
│   └── package.json        # Frontend dependencies
├── server/                 # Backend Node.js application
│   ├── src/
│   │   ├── types/          # TypeScript type definitions
│   │   └── server.ts       # Main server file
│   └── package.json        # Backend dependencies
└── README.md              # This file
```

## 🌟 Key Components

### Frontend Components
- **EditorPage**: Main collaboration workspace
- **HomePage**: Landing page with room joining form
- **WorkSpace**: Core editing area with file tabs and editor
- **Sidebar**: Navigation and user management
- **DrawingEditor**: Real-time drawing collaboration
- **ChatList**: Real-time messaging system

### Backend Features
- **Socket.IO Server**: Handles real-time communication
- **Room Management**: Manages user connections and room states
- **File Synchronization**: Syncs file changes across users
- **User Management**: Tracks user presence and activities

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [CodeMirror](https://codemirror.net/) for the code editing capabilities
- [TLDraw](https://tldraw.dev/) for the drawing functionality
- [Socket.IO](https://socket.io/) for real-time communication
- [Tailwind CSS](https://tailwindcss.com/) for the styling framework

---

**Happy Collaborating! 🎉**
