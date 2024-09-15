## Node-Chatroom-App

A real-time chat application built with **WebSockets** and **Socket.IO**, enabling seamless, bi-directional communication between clients and the server. This allows for messages and data to be exchanged in real time, maintaining a persistent connection throughout the session.

### Live Demo:
[Try the live chat application here!](https://node-chatroom-app-production.up.railway.app/)

### Key Features:
- **Real-Time Messaging:** Clients can send and receive messages instantly, thanks to the WebSocket protocol.
- **Socket.IO Integration:** Simplifies the WebSocket setup, making it easy to manage events and broadcast messages.
- **Room Functionality:** Users can join specific chat rooms, and messages are broadcasted only to users within the same room.
- **Geolocation Sharing:** Users can share their current location with other participants in the chat.
- **Auto-scroll:** Automatically scrolls the chat window for the latest messages when new content is received.
  
### Technologies Used:

- **Node.js:** Back-end server framework.
- **Express.js:** For creating the server and handling HTTP requests.
- **Socket.IO:** To handle WebSocket connections and real-time communication.
- **Mustache.js:** For rendering dynamic message templates on the client side.
- **Moment.js:** For formatting timestamps in the chat.

### How It Works:
1. **Server-Client Communication:** 
   - The server sets up WebSocket connections using Socket.IO, allowing the client to emit events and listen for responses.
   - Both server and client can send and receive data over a persistent connection.
   
2. **Room-Based Communication:** 
   - Users can join different chat rooms, and messages are broadcasted only to users within the same room.
   
3. **Real-Time Geolocation:** 
   - Users can share their location via the browser's Geolocation API, which sends coordinates to the server and shares them with other users as a clickable Google Maps link.

### Getting Started:
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/lucane-asturias/node-chatroom-app.git
   cd node-chatroom-app
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Application:**
   ```bash
   npm start
   ```

4. **Access the Application:** 
   Open your browser and navigate to `http://localhost:3000`.
