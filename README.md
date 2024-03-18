<p align="center">
  <img src="https://img.shields.io/badge/language-Java-orange.svg" alt="Language">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
</p>

# Multi-Client Chat Server

A simple multi-client chat server implemented in Java using socket programming and threading.

## Features

- :computer: Accepts connections from multiple clients simultaneously
- :speech_balloon: Clients can send messages to the server, which are then broadcasted to all other connected clients
- :octocat: Server can be gracefully shut down using the "/shutdown" command

## Usage

1. Compile the Java files: `javac MultiClientChatServer.java Client.java`
2. Start the server: `java MultiClientChatServer`
3. Run multiple instances of the client: `java Client`
4. Enter messages in the client terminals to chat with other connected clients
5. To shut down the server, type "/shutdown" in the console where the server is running

## Files

- `MultiClientChatServer.java`: Main server code
- `Client.java`: Client code for connecting to the server

## Note

- :warning: Make sure to adjust the host and port values in the `Client.java` file if the server is running on a different host or port.

## License

This project is licensed under the [MIT License](LICENSE).
