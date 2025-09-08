# 💎 GemChat: An AI-Powered Real-Time Chat App

## 🚀 Live Demo

[![Live Preview](https://img.shields.io/badge/Live%20Preview-Click%20Here-blue?style=for-the-badge&logo=netlify)](https://gemchat-live.netlify.app)

---

### Project Description
GemChat is a modern, real-time chat application built with the MERN stack. It allows users to collaborate on projects while communicating seamlessly. The key feature of this application is its integration with Google Gemini, which provides AI-powered chat capabilities for instant assistance with code, logic, and more.

---

### Key Features
- 🗣️ **Real-time Messaging**: Instant and seamless communication between users powered by Socket.IO.
- 🤖 **AI-Powered Chat**: Integrated with Google Gemini to provide intelligent coding and development assistance.
- 🔐 **User Authentication**: Secure user registration and login system.
- ⚡ **High Performance**: Optimized with Redis for fast caching and improved performance.

---

### Tech Stack
- **Frontend**:
    - **React**: A JavaScript library for building user interfaces.
    - **Vite**: A fast build tool for modern web projects.
    - **Tailwind CSS**: A utility-first CSS framework for rapid UI development.

- **Backend**:
    - **Node.js**: The runtime environment for the server.
    - **Express.js**: A fast, unopinionated web framework for Node.js.
    - **Socket.IO**: A library for real-time, bidirectional communication.

- **Database**:
    - **MongoDB Atlas**: A cloud-based NoSQL database for storing user and project data.
    - **Redis**: An in-memory data store for caching and real-time operations.

- **AI Integration**:
    - **Google Gemini API**: Used for AI-powered chat functionalities.

---

### Folder Structure
This project follows a polyrepo architecture with separate repositories for frontend and backend.
```
GemChat/
├── frontend/             # React frontend codebase
│   └── src/
├── backend/              # Node.js backend codebase
│   └── server.js
├── .gitignore            # Git ignore file
└── README.md
```
---

### Deployment
This project follows a polyrepo architecture for cleaner deployment.
- **Live App**: Deployed on **Netlify**.
- **Frontend Repository**: [GemChat-frontend](https://github.com/aarjav-jain151/GemChat-frontend)
- **Backend Repository**: [GemChat-backend](https://github.com/aarjav-jain151/GemChat-backend)
