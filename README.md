# Server-Client
COMPANY: CODTECH IT SOLUTION

NAME: NITHIKAMALINI S                                            

INTERN ID: CT04DH1694

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

# TASK DESCRIPTION
The client-server model is a communication framework where a centralized server interacts with multiple clients. In a chat application, the server acts as a central hub that facilitates message exchange between users (clients). The server runs continuously, listening on a specific port for incoming connections. Once a client connects, the server spawns a dedicated thread for that client, ensuring that multiple clients can communicate simultaneously without interference.

Each client connects to the server using a socket and sends messages which the server receives. The server then broadcasts the message to all other connected clients using their respective output streams. This setup allows real-time messaging, ensuring that all participants receive messages promptly.

The use of Java Sockets enables reliable TCP-based communication, while multithreading on the server ensures scalability—handling multiple clients concurrently. The client-side application includes threads as well to simultaneously send and receive messages without blocking.

This architecture is simple yet powerful, suitable for chat systems, multiplayer games, or collaborative tools. By decoupling the client and server responsibilities, the system maintains a clean structure, allowing for easy expansion, such as authentication, chat rooms, or file sharing in future enhancements.
#OUTPUT
<img width="1207" height="320" alt="Image" src="https://github.com/user-attachments/assets/bbce0ee4-e98c-4577-ab49-e7cdb1a0199e" />
