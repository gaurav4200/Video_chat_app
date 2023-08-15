## Video Chat Application using WebRTC, React and Socket.io

This repository contains a video chat application built using WebRTC, Socket.io, HTML, CSS, and React. The application allows users to have real-time video conversations in a web browser without requiring any additional plugins or software.

### Features

Real-time video chat between two users.
WebRTC for peer-to-peer video and audio communication.
Socket.io for signaling and establishing connections.
User-friendly interface built with React, HTML, and CSS.
Prerequisites
Node.js and npm installed on your machine.
Modern web browser that supports WebRTC.
Installation
Clone the repository:

    git clone https://github.com/gaurav4200/Video_chat_app

Navigate to the project directory:

    cd video-chat-app

Install the dependencies:

    npm install

Usage
Start the development server:
npm start
Open your web browser and navigate to http://localhost:3000.

Enter your name and click "Join Chat".

Share the generated link with your friend to invite them to the video chat.

Once your friend joins using the shared link, you will be able to have a video chat.

How It Works
The application uses React to create the user interface, where users can enter their names and start the chat.

When a user clicks "Join Chat," the application uses Socket.io to establish a connection with the server and exchange signaling data.

WebRTC is used to establish a direct peer-to-peer connection between the users' browsers for video and audio streaming.

The application uses HTML and CSS to create a responsive and visually pleasing user interface.

Folder Structure

public/: Contains the static HTML file and other assets.
src/: Contains the React components and application logic.
components/: Contains React components used in the application.
utils/: Contains utility functions for WebRTC and Socket.io.

Acknowledgments

This application is built upon the foundation of WebRTC, Socket.io, React, and various other open-source libraries. Special thanks to the developers and communities behind these technologies.

License

This project is licensed under the MIT License.

Feel free to contribute to the project by opening issues, submitting pull requests, or using it as a starting point for your own applications. Happy video chatting! 🎥📞
