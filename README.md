# 💬 Let's Discuss - Real-time Chat Application -
A simple and elegant real-time chat application built using Node.js, Socket.io, HTML, CSS, and Vanilla JavaScript. This project demonstrates how real-time communication works using WebSockets and provides a fun way to explore real-time messaging in action.

## 📌 Features : 

1) 🔗 Real-time communication using Socket.io
2) 💬 Instant message broadcasting to all connected users
3) 🎵 Message notification sound
4) 📸 Simple and clean UI with custom styles and icon
5) 🌐 Lightweight and browser-based (no frontend frameworks)
6) 💡 Built using only HTML, CSS, and JavaScript

## 🧰 Tech Stack
### Frontend: HTML, CSS, JavaScript
### Backend: Node.js, Socket.io
### Media: Custom notification sound and chat icon

## 📁 Project Structure

Let's-Discuss-Chat-Application/
├── css/
│   └── style.css               # Styling for the chat UI
├── js/
│   └── client.js               # Frontend Socket.io logic
├── nodeServer/
│   ├── index.js                # Backend server using Socket.io
│   └── node_modules/           # Installed npm packages
├── chat.png                    # Chat icon used in the UI
├── index.html                 # Main HTML file
├── package.json               # Project metadata and dependencies
├── package-lock.json          # Lock file for npm packages
├── ting.mp3                   # Notification sound for messages
├── web_socket.txt             # Info/reference about WebSocket (optional)


## 🛠️ Setup Instructions
1) Clone the repository :
git clone https://github.com/Abhishek-Savita-3012/Let-s-Discuss-Chat-Application.git
cd Let-s-Discuss-Chat-Application

2) Install dependencies :
cd nodeServer
npm install

3) Start the server :
node index.js

4) Open the application :
   
Open your browser and go to:
http://localhost:8000
Now open the same URL in multiple tabs or devices to test real-time chat.

## 📌 How it works
The backend (nodeServer/index.js) uses Socket.io to manage real-time connections.
Each client connects to the server and emits messages using client.js.
Messages are broadcast to all connected clients.
A sound (ting.mp3) is played when a new message is received.

## 🚀 Future Enhancements
User authentication
Support for private messages or rooms
Message timestamps
Message history persistence with MongoDB
Typing indicators
Better UI/UX

## 🙋‍♂️ Author
Abhishek Savita
GitHub: @Abhishek-Savita-3012

## 📄 License
This project is licensed under the MIT License
