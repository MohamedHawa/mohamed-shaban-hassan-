# Multi-Client Communication Project

This project contains implementations for multi-client communication scenarios, including chat applications and a tic-tac-toe game.

## Directories

1. **Chat Between Two Clients**
    - **Description:** This directory contains a server and two client implementations. The server controls communication between the clients, allowing one client to send messages to the other.
    - **How to Run:** 
        - Start the server.
        - Run two client instances, each identifying the other client to connect with.
        
2. **Chat Room**
    - **Description:** This directory contains a server and client implementations. The client can broadcast messages to all other clients connected to the server.
    - **How to Run:** 
        - Start the server.
        - Run one or more client instances to connect to the chat room and start broadcasting messages.
        
3. **Tic-Tac-Toe (XO)**
    - **Description:** This directory contains a server and client implementations for playing tic-tac-toe (XO). Two clients can connect to the server to play the game.
    - **How to Run:** 
        - Start the server.
        - Run two client instances to connect to the server and play tic-tac-toe.

## Usage

- Each directory contains a `server.py` and `client.py` file.
- Run the `server.py` file first, then run the `client.py` file(s) for the desired functionality.
- Follow the instructions in each client's console to interact with the server and other clients.

## Dependencies

- Python 3.x
- Socket programming libraries (built-in)

## Note

- This project is for educational purposes and may not be suitable for production environments.
