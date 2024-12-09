
# Realtime Chat App with Websockets

This is a simple **Realtime Chat Application** built using **Node.js**, **Express**, and **Socket.io** on the backend, and **Vanilla JavaScript** for the frontend. The app supports real-time messaging between users, with a custom UI inspired by popular chat applications.

## Features
- Real-time messaging with WebSockets
- Simple and clean chat interface
- User-friendly design
- Custom UI with a modern, dark theme
- No dependencies other than Node.js, Express, and Socket.io
- Easy to set up and run locally

## Tech Stack
- **Backend**: Node.js, Express, Socket.io
- **Frontend**: Vanilla JavaScript, HTML, CSS (Custom UI)
- **WebSocket Protocol**: For real-time communication

## Installation

### Prerequisites
- **Node.js** and **npm** (Node Package Manager) must be installed.  
  Download and install from [Node.js official website](https://nodejs.org/).

### Steps to Run the Application Locally

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Start the application:
   ```bash
   npm start
   ```

   The app will start the server on `http://localhost:3000`.

4. Open your browser and visit `http://localhost:3000` to start using the chat application.

## How It Works
- The server is built using **Node.js** and **Express**, with **Socket.io** to handle real-time communication.
- On the frontend, **Vanilla JavaScript** handles the user interface interactions, including sending and receiving messages via WebSocket.
- The chat room is automatically updated in real-time when new messages are sent.
  
### WebSocket Communication:
- When a user sends a message, it's emitted to the server through **Socket.io** and broadcast to all connected clients, ensuring that all users in the room see the new message in real time.

## Features of the UI
- **Responsive design** that adjusts to different screen sizes.
- **Dark theme** similar to Discord’s UI.
- Users can view the room name and the list of connected users.
- **Message input field** and **send button** to send messages.
- **Message bubbles** styled with a clean, modern look.

## File Structure

```
/public
  /css
    - style.css            # Custom UI styles
  /js
    - main.js              # JavaScript for the frontend
  index.html               # Main HTML structure for the frontend
/server
  - server.js              # Node.js server with Express and Socket.io
package.json               # Project dependencies and scripts
README.md                  # Project documentation
```

## Usage
Once the server is running:
1. Open the application in your browser.
2. The chat room is ready to use.
3. Send messages and see them appear in real-time for all users connected to the room.

## Screenshots

### Example UI

![Chat App Screenshot](path-to-screenshot)

## Contributing

Feel free to fork the repository and submit pull requests! Contributions are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
