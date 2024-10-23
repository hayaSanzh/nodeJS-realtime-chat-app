
# Node.js Real-Time Chat App

A simple real-time chat application built using **Node.js**, **Socket.io**, and **Express.js**. This app allows multiple users to join a chat room, send messages, and see other users' messages in real-time.

## Features

- Real-time messaging using **Socket.io**
- Notifications when users join or leave the chat
- Display of active users in the chat room
- Clean and minimal user interface
- Responsive design for both desktop and mobile views

## Technologies Used

- **Node.js**: Backend JavaScript runtime environment
- **Express.js**: Web framework for Node.js
- **Socket.io**: Enables real-time, bidirectional communication
- **HTML/CSS/JavaScript**: Frontend technologies for building the user interface

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/hayaSanzh/nodeJS-realtime-chat-app.git
   ```

2. Navigate into the project directory:
   ```bash
   cd nodeJS-realtime-chat-app
   ```

3. Install the necessary dependencies:
   ```bash
   npm install
   ```

4. Start the server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Project Structure

- **public/**: Contains static assets like the HTML, CSS, and client-side JavaScript files.
  - `index.html`: The main HTML file for the chat interface.
  - `style.css`: CSS file for styling the chat interface.
  - `chat.js`: Client-side JavaScript that handles socket connections and DOM updates.

- **server.js**: Main Node.js file that sets up the server and handles Socket.io connections.

- **utils/**: Contains utility functions used within the server (e.g., handling usernames, messages, etc.).

## Future Improvements

- Private messaging between users
- Support for multiple chat rooms
- Saving chat history in a database
- User authentication for secure access

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
