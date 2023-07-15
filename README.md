# Real-Time Chat Application

This is a real-time chat application built using Node.js, Express, and Socket.io. It allows users to communicate with each other in real-time, exchange messages, and see who is typing. The application uses Socket.io for handling real-time communication between the server and clients.

## Features

Real-time messaging: Users can send and receive messages instantly.

Typing indicator: Users can see when someone is typing a message.

Private messaging: Users can send private messages to specific users.

Username validation: Usernames are checked for availability upon connection.

User disconnection handling: When a user disconnects, others are notified.

## Installation
1.Clone the repository:
git clone https://github.com/your-username/real-time-chat-app.git

2.Install the dependencies:
cd real-time-chat-app
npm install

3.Run the server:
npm start
Open your web browser and visit http://localhost:3000.

## Usage
1.Enter your desired username in the username input field and click the "Connect" button.

2.Once connected, you will see a list of online users on the right side.

3.To send a message, type your message in the input field at the bottom and press "Enter" or click the "Send" button.

4.When someone else is typing, you will see a typing indicator below their username.

5.To send a private message to a specific user, click on their username from the online users list, and a private chat window will open.

6.To disconnect from the chat, simply close your browser or click the "Disconnect" button.

## Contributing
Contributions are welcome! If you find any bugs or want to add new features, please open an issue or submit a pull request. Make sure to follow the existing code style and include appropriate tests for new features.

