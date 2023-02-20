# Socket Programming 1
## Client-Server in python
This is a simple implementation of a client and server in Python that communicate with each other over a TCP socket. The client sends a message containing the client's name and a number between 1 and 100 to the server. The server receives this message, extracts the client's name and number, then generates a random number between 1 and 100, calculates the sum of the client's number and the server's number, and then sends a message back to the client containing the server's name and the random number. The client receives this message, extracts the server's name and number, calculates the sum of the client's number and the server's number, and displays this information on the console.
## Installation
To run the client and server code, you need to have the latestest version of python installed. 
Once this is installed, clone or download the repostory
## Usage
- Open the terminal window and navigate to the TCPserver.py file then run it, from here the server will start running and listening for incoming connections
- Open the terminal window and navigate to the TCPclient.py file then run it, from here the server will start running.
It will prompt you to enter your name followed by a number 1 - 100. From here the client will send a message to the server, recieve a response from the server, calculate the sum of the clients' number and the servers number, and display the information on the console.  
## License
Code is released under the MIT License 
