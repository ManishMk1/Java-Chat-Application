# Java Chat Application

## Overview

A Java chat application is a multi-user communication platform developed using Java. It utilizes Swing to create user-friendly interfaces and socket programming to manage real-time data exchange between clients across networks. The application follows a client-server model, with the server handling multiple client connections simultaneously using threading techniques. Data such as user profiles and chat histories are stored in a MySQL database, ensuring that all communication and user information are managed effectively. This project integrates essential concepts from Java programming, computer networks, and database management, providing a comprehensive learning experience in building networked applications.

## Key Technologies

- **Java**: Core programming language used for development.
- **Swing**: Java library for building graphical user interfaces.
- **Socket Programming**: Enables real-time data exchange across networks.
- **MySQL**: Backend database for storing user data and chat logs.
- **Computer Networks**: Fundamental for handling data transmission and connectivity.

## Contributors

- Prajwal Gandhi - 1000015996
- Manish Kumar - 1000016090
- Aatman Sah - 1000015844

## Usage

To start using this chat application, users need to run the server program first, followed by launching the client interface. Users can log in and begin chatting with other users connected to the same server.

## Start the Code from
- First, we start the server from this file: `./network/ServerWorker.java`
- Then, we have to run the user code for the users means we have to run the user code for multiple times for multiple users: `./utils/UserScreen.java`
- Then, we access the chat application and communicate by doing the chat.

## Configuration File

The application uses a `config.properties` file to manage environment variables such as database connection settings, server port, and other configurable parameters. This file allows for easier adjustments and maintenance without altering the core code:

Example `config.properties`:
```properties
serverPort=8080
dbUrl=jdbc:mysql://localhost:3306/chatdb
dbUser=admin
dbPassword=12345

