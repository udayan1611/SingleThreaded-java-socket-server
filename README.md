# Simple Java WebServer

This is a basic client-server implementation in Java using **sockets**.  
It includes a single-threaded server that listens for connections and a client that connects to it.

## Features
- Server listens on port `8010`
- Accepts incoming client connections
- Sends and receives simple text messages
- Demonstrates socket programming in Java

1. Compile
   javac Server.java
   //open another terminal
   javac Client.java

3. Start the server
  java Server

4. Run the client

  Open a new terminal:

  java Client

You should see:

Received from server: Hello from the server.

## Future Work

Add multithreading (handle multiple clients at once)

