# Chatapplication
a simple chat application with multithread and gui 

README

Project Name: Simple Chat Application in Java

Description: This is a simple chat application written in Java. It uses a client-server architecture, where the server listens for incoming connections from clients and forwards messages between them.

Features:

Send and receive messages to and from other clients
Broadcast messages to all active clients
Send private messages to specific clients
See a list of active clients
Log out of the server
To run the application:

Compile the code using the following command:
javac -d bin src/client/Client.java
Run the server using the following command:
java -cp bin client.Client [username] [portNumber] [serverAddress]
Run the client using the same command, but with the portNumber and serverAddress of the server.
Example:

java -cp bin client.Client Alice 11926 2.tcp.ngrok.io
Usage:

Once the client is running, you can send and receive messages by typing them into the console. To send a message to all active clients, simply type the message and press enter. To send a private message to a specific client, type @username<space>yourmessage without quotes. To see a list of active clients, type WHOISIN. To log out of the server, type LOGOUT.

Troubleshooting:

If you are having trouble connecting to the server, make sure that the server is running and that the portNumber and serverAddress are correct. If you are still having trouble, please consult the documentation for the Java networking library.
