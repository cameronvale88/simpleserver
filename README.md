# simpleserver
Rudimentary file server that will stream one file to a client.

Requirements: sockets, sys

In order to run the programs, run the server proogram from the computer you'd like to serve files from and type "python3 simpleserver_server.py". The program will ask you for the file you'd like to send. It's best to place the file and the programs in the same directory.

On the client computer, type "python3 simplerserver_client.py" and the client should automatically recieve the file. 

Remember to change firewall rules appropriately.

## NOTE: This program is designed to work only on lan.
