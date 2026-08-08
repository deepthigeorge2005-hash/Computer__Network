# Network Lab Experiment
Socket Programming 

## Aim
To implement TCP client-server applications using socket programming and enable communication between the client and server for processing and exchanging data.

## Commands Used
socket() – Create a TCP socket
bind() – Assign IP address and port to the server
listen() – Wait for client connections
accept() – Accept a client connection
connect() – Connect the client to the server
send() – Send data through the socket
recv() – Receive data through the socket
close() – Close the socket connection
inet_pton() – Convert IP address to binary form
htons() – Convert port number to network byte order
strlen() – Find string length
strcpy() – Copy strings
toupper() – Convert characters to uppercase

## Procedure
Create a TCP socket at the server and client.
Bind the server socket to port and start listening.
Connect the client to the server using the server IP address.
Enter the required input at the client.
Send the input data to the server using TCP.
The server processes the received data.
Send the processed result back to the client.
Display the result at the client.
Close the socket connections.

## Output
The client successfully connects to the server, sends the required data, and receives the processed results from the server.

## Conclusion
TCP client-server communication was successfully implemented using C socket programming. The client and server successfully exchanged data and performed the required operations.
