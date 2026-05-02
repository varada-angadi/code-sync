# CodeSync - Real-Time Collaborative Code Editor

**CodeSync** is a web application that allows multiple users to collaborate on code in real-time. Built with **React**, **Monaco Editor**, **Socket.IO**, and **Yjs**, it provides a smooth, interactive, and conflict-free coding experience. The backend is powered by **Node.js** and **Express** with **MongoDB** for storage.

---

## Features

- **Real-Time Collaboration** – Edit the same document simultaneously with other users.
- **Monaco Editor** – A powerful, VS Code-inspired code editor for a rich editing experience.
- **Real-Time Sync** – Uses **Yjs** (CRDT) for conflict-free, real-time synchronization across all users.
- **Socket.IO** – Enables instant communication between clients and the server.

---

## Tech Stack

- **Frontend**: React, Monaco Editor
- **Backend**: Node.js, Express.js, Socket.IO
- **Real-Time Sync**: Yjs (CRDT)
- **Deployment**: Docker (for containerization) and AWS (for cloud hosting)

---

## Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/CodeSync.git
cd code-sync
```

### 2. Install dependencies
```
npm install
```

### 3. Start Backend & Frontend under their folder
```
npm start
npm start      
```
