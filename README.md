# Chat_App
# 💬 SyncChat: Real-Time Private & Public Messaging App

SyncChat is an event-driven, full-stack web application that enables multi-user real-time communication. Powered by WebSockets via Socket.io, the platform supports instant public room broadcasting alongside secure, low-latency one-to-one private messaging channels.

### 🚀 Live Demo
Try the interactive chat application live: **[Insert Your Live Link / Heroku / Render Link]**

### 🛠️ Key Features
* **Bi-Directional Communication:** Replaced traditional HTTP polling with full-duplex **Socket.io** channels to deliver messages instantly with sub-millisecond latency.
* **Dual-Channel Architecture:** Isolated network event emitters to support both multi-user open lobby rooms (Public) and handshake-authenticated single streams (Private).
* **Modern ES6+ Logic:** Written entirely in modular, modern JavaScript using advanced arrow formatting, asynchronous promises, and structured event delegation.
* **State Synchronization:** Integrated real-time client-side indicators including dynamic active user listings and real-time message timestamps.

### 🧰 Tech Stack
* **Frontend:** HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+)
* **Backend Runtime:** Node.js, Express.js
* **Real-Time Engine:** Socket.io (WebSockets)
