# Comp3100 Project by Kurtis Fraser (45967407)

# MyClient.java (Client for Stage 1)
A client class that does the following:
1. Performs handshake with the server
2. Gets a list of servers
3. Determines the largest server and collects a list of all servers that share a type with the largest
4. Performs a loop assigning jobs to each of the largest servers in a sequential order until there are no jobs left
5. Closes the connection with the server

# ServerObj.java
A class that creates objects that store all the relevant data from a Server.

# MyServer.java (Unused)
Creates a server and establishes a connection with the client
#Note doesn't really work at this stage and not much work has been done on it

# MyClientFC.java (Unused)
A client class that does the following:
1. Performs handshake with the server
2. Loops until it has scheduled all jobs according to the First Capable (FC) Algorithm
5. Closes the connection with the server

# MyClientPt2.java (Client for Stage 2)
A client class rework to support trialling multiple different algorithm functions.

Most successful algorithm was a modified Best Fit algorithm that starts searching for the first capable server halfway through the server list.