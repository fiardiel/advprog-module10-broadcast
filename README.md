# Advprog Module 10 - Broadcast

## Original code, and how it run
![screenshot1](img/ss1.png)

Everytime the client sends a message, the server will broadcast the message to all connected clients. The server will also print the message to the console.

## Modifying port
 
We need to change the port in both the `server.rs` and `client.rs` file both in the main functions. The server uses TCP connection and the client uses websocket protocol.