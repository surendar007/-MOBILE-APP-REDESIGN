# -MOBILE-APP-REDESIGN

COMPANY NAME : CODTECH IT SOLUTIONS

NAME : SURENDAR

INTERN ID :CT04WV112

DOMAIN NAME : UI/UX DESIGN

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH KUMAR
DESCRIPTION : A client-server chat application is a network-based program that enables multiple users to communicate with each other through a central server. This project uses Java sockets and multithreading to establish a real-time chat system where multiple clients can connect to the server and exchange messages. The main goal is to demonstrate core networking concepts in Java and efficient use of multithreading to handle simultaneous client connections.

In this application, the server is the central point of communication. It listens for incoming connections from multiple clients. Each client connects to the server via a socket, and once connected, the server creates a dedicated thread for each client to handle communication individually. This ensures that all clients can send and receive messages concurrently without interfering with one another.

The Java Socket API provides the tools necessary to establish communication over TCP (Transmission Control Protocol). The ServerSocket class is used on the server side to wait for connection requests, while the Socket class is used on the client side to initiate the connection. Once the connection is established, input and output streams are used to send and receive messages.

To handle multiple users, multithreading is used. When a client connects, the server spawns a new thread, specifically a ClientHandler thread, which continuously listens for messages from that client and broadcasts those messages to all other connected clients. This ensures non-blocking communication and real-time message delivery across all clients.

The client-side interface is typically a simple command-line interface (CLI), allowing users to type messages and see messages from others. Each client connects to the server using an IP address and port number. Messages typed by the user are sent to the server, which then forwards them to every connected client.

OUTPUT :

![Image](https://github.com/user-attachments/assets/948e9707-2ef6-4344-9828-205f4ad349cc)

