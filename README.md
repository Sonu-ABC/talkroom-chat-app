# 💬 Talkroom — Real-Time Chat Application

A full-stack real-time chat application built with the MERN stack and Socket.io. Talkroom supports instant direct messaging, group channels, file sharing, and live progress tracking for uploads and downloads.

🔗 **Live Demo:** [https://talkroom-chat-app.vercel.app](https://talkroom-chat-app.vercel.app)

---

## ✨ Features

- 🔐 **Secure Authentication** — JWT-based login & signup with bcrypt password hashing and HTTP-only cookies
- ⚡ **Real-Time Messaging** — Instant bidirectional communication powered by Socket.io
- 👤 **Direct Messages** — One-on-one private chats with contacts
- 📢 **Channels** — Create and join group channels for multi-user conversations
- 📁 **File Sharing** — Send images and documents with real-time upload/download progress tracking
- 🖼️ **Profile Customization** — Set profile pictures and choose avatar colors
- 🔔 **Live Contact List** — DM list automatically reorders to show most recent conversations at the top
- 📱 **Responsive UI** — Works on desktop and mobile screens

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|---|---|
| React 18 | UI framework |
| Vite | Build tool & dev server |
| Zustand | Global state management |
| Socket.io Client | Real-time communication |
| React Router DOM | Client-side routing |
| Tailwind CSS | Styling |
| Radix UI | Accessible UI components |
| Axios | HTTP requests |
| Moment.js | Date/time formatting |

### Backend
| Technology | Purpose |
|---|---|
| Node.js + Express | Server & REST API |
| MongoDB + Mongoose | Database |
| Socket.io | WebSocket server |
| JWT | Authentication tokens |
| bcrypt | Password hashing |
| Multer | File uploads |
| Cookie Parser | Cookie management |
| dotenv | Environment variables |

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas account (or local MongoDB)

### 1. Clone the repository
```bash
git clone https://github.com/Sonu-ABC/talkroom-chat-app.git
cd talkroom-chat-app

### 2. Setup the Server
```bash
cd server
npm install
```

Create a `.env` file inside the `server` folder:
```env
PORT=8080
JWT_KEY=your_secret_key_here
ORIGIN=http://localhost:5173
DATABSE_URL=your_mongodb_connection_string
```

Start the server:
```bash
npm run dev
```

### 3. Setup the Client
```bash
cd client
npm install
```

Create a `.env` file inside the `client` folder:
```env
VITE_SERVER_URL=http://localhost:8080
```

Start the client:
```bash
npm run dev
```

### 4. Open the app
Visit **http://localhost:5173** in your browser.
