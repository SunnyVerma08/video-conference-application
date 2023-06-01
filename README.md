## Video Conference Application

This is a simple video conference application built using Node.js, Express, Socket.IO, and PeerJS. It allows users to create or join a video conference room and communicate with other participants via video and text chat.

### Installation

1. Clone the repository or download the source code.
2. Navigate to the project directory.

```bash
cd video-conference-application
```

3. Install the dependencies using npm.

```bash
npm install
```

### Usage

1. Start the server.

```bash
npm start
```

2. Open a web browser and access the application at `http://localhost:3030`.
3. Enter a unique room ID or leave it empty to generate a random room ID.
4. Share the room ID with other participants to join the same room.
5. Grant access to the camera and microphone when prompted by the browser.
6. Use the controls to mute/unmute audio, pause/resume video, and access other features like security, participants, and chat.
7. To leave the meeting, click on the "Leave Meeting" button.

### Dependencies

The application relies on the following dependencies:

- **ejs** : A simple and flexible templating engine for rendering HTML templates.
- **express** : A fast and minimalist web framework for Node.js.
- **peer** : A library for creating WebRTC connections between peers for audio, video, and data communication.
- **socket.io** : A library that enables real-time, bidirectional, and event-based communication between the browser and the server.
- **uuid** : A library for generating unique identifiers (UUIDs).

### Acknowledgments

This project was developed as a simple video conference application using various web technologies and libraries. It can serve as a starting point for building more complex real-time communication applications. Feel free to modify and enhance it according to your requirements.

### Features

The application currently includes the following features:

- Video conferencing: Users can join a room and participate in a video conference with other users.
- Grid view: The video streams of other participants in the room are displayed in a grid.
- Chat window: Users can chat with each other via a text chat window.

### Limitations

This application is a simple proof-of-concept and has the following limitations:

- Lack of security features: The application does not have user authentication or encryption, making it unsuitable for production use.
- No recording functionality: The application does not support recording and saving video conferences.
- No file sharing: There is no capability to share files during video conferences.

### Future Work

In the future, I would like to add the following features to this application:

1. Security features, such as user authentication and encryption.
2. The ability to record and save video conferences.
3. The ability to share files during video conferences.

Please note that this application is currently a simple proof-of-concept and is not meant for production use. Adding these features will enhance the functionality and security of the application.
