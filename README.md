# Python TCP Socket Connection
<h2>Description</h2>


This project demonstrates a simple TCP server implementation in Python using the socket module. The server listens for incoming connections, sends a greeting message to the client, and then closes the connection.

<h2>Languages and Utilities Used</h2>

 - <b>Python3</b> 


<h2>Environments Used </h2>

- <b>Kali Linux</b> 
- <b>Visual Studio Code</b> 



<h2>Program walk-through:</h2>

- TCP Socket: Creates a TCP/IP socket using socket.AF_INET and socket.SOCK_STREAM.

- Server Binding: Binds the server to the host and port.

- Connection Handling: Listens for incoming connections and accepts them.

- Message Sending: Sends a greeting message to the connected client.

- Connection Management: Closes the client connection after sending the message.

### How It Works

1. *Create a TCP Socket*: Uses socket.AF_INET and socket.SOCK_STREAM to create a TCP/IP socket.
2. *Bind to Host and Port*: Binds the socket to the host (hostname) and a port (444).
3. *Listen for Connections*: Listens for up to 3 incoming connections.
4. *Accept Connections*: Accepts incoming client connections and prints the client's address.
5. *Send Message*: Sends a greeting message to the client.
6. *Close Connection*: Closes the client socket after the message is sent.

### Usage

To run the server:

1. Execute the script:
   python server.py
   

2. The server will start listening for incoming connections on port 444 and will send a greeting message to each connected client.

### Requirements

- Python 3.x
- No additional dependencies

