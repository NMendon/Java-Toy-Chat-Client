# Java-Toy-Chat-Client
We will make a simple java project, a chat client. This project has the following use cases for 
bv 0.1
1. A user should be able to start a chat client and at first be able to type text onto the command line/UI and that will be sent to a server and logged there.
2. The user can send a command to end the chat program:
	/end -> ends the program
	/find <text> -> Finds text in historical chat and displays it.
3. The server should store the messages in a text file. 

v 0.2: 
A user should be able to see a list of people connected to server using /who
To chat to a user a person the command is 
/connect <person name>
You can only connect to one person at a time to chat.
Once a person has connected to another sending a message to the other person should make it appear on the other personÎéÎ÷s terminal.

What we can learn from v 0.1
You should be able to make classes that represent a server and a client and define interfaces that can send and receive messages
You should be able to 
Open a socket to a given address and port.
Poll a socket for any messages received.
Send a message over a socket.
You will learn how to accept user input.
Save messages to a file
Search messages in a file.


