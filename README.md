Concurrent Client/Server Socket Communication in F#

### Overview

Project 1 demonstrates the implementation and testing of a concurrent client/server socket communication system using F#. It includes the creation of a server application capable of handling multiple client connections simultaneously and a client application that communicates with the server over a TCP/IP protocol suite.

### Key Features

- **Concurrent Communication**: Supports simultaneous communication between multiple clients and the server.
- **Efficient Socket Handling**: Implements efficient socket management for reliable and scalable communication.
- **Exception Handling**: Incorporates robust exception handling mechanisms for reliable operation.

### Usage

To execute the client/server communication system, follow the setup instructions provided in the project directory. Use the provided commands to compile and run the applications.
### Requirements

- **Server-Side Script**: Capable of handling several client connections simultaneously, improving system performance through concurrent processing.
- **Client-Side Script**: Connects to the server, sends commands, and displays responses asynchronously.
- **Exception Handling**: Robust exception management to ensure reliable system operation.

### Compilation and Execution Instructions

1. Create a project directory.
2. Initialize server and client applications with `dotnet new console --language F# -o server` and `dotnet new console --language F# -o client`, respectively.
3. Rename `Program.fs` to `client.fs` and `server.fs` in their respective directories.
4. Compile the projects using `dotnet build` within each directory.
5. Start the server and client(s) using `dotnet run`.

### Code Structure

- **Server and Client Scripts**: Manage connections, handle client requests, and asynchronous task handling for each client.
- **Exception Handling**: Includes production and processing of error codes for reliable operation.

### Results and Execution

- Demonstrates the server's ability to handle multiple clients, process commands, and manage exceptions.
- Detailed execution results, including test cases and screenshots, are provided.
