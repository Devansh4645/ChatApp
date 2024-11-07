# ChatApp

A real-time chat application built using Node.js and Socket.io. ChatApp enables users to connect, communicate instantly, and enjoy a responsive user interface designed with simplicity in mind.

## Features

- **Real-time Messaging**: Instant message exchange using WebSockets.
- **Multi-User Support**: Allows multiple users to join and chat together.
- **Responsive UI**: User-friendly interface compatible with both desktop and mobile devices.
- **Message Notifications**: Visual notifications for new messages.
- **Customizable Username**: Set your username upon joining.

## Technology Stack

- **Node.js**: Backend server
- **Express**: Framework for handling routes
- **Socket.io**: Real-time, bi-directional communication
- **HTML/CSS/JavaScript**: Frontend user interface

## Installation

To run this project locally, ensure you have **Node.js** and **npm** installed. Follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Devansh4645/ChatApp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ChatApp
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   node server.js
   ```

5. Open your browser and go to:

   ```
   http://localhost:3000
   ```

## Usage

1. Start the server as described above.
2. Open the application in a browser.
3. Enter a username and join the chat room.
4. Begin messaging with other connected users.


## Images
![Uploading image.png…]()


## Project Structure

- **server.js**: Main server file that handles socket connections.
- **/public**: Contains frontend assets.
  - **index.html**: Entry point for the application UI.
  - **styles.css**: Basic styling for the chat interface.
  - **client.js**: Client-side socket connection handling.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add new feature"
   ```

4. Push to the branch:

   ```bash
   git push origin feature-name
   ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
