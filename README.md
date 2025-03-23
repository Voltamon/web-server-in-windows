# Simple HTTP Server in C

This project implements a minimal multi-threaded HTTP server in C using the Winsock2 API on Windows. The server listens for incoming connections on port 8080 and handles basic HTTP GET requests.


## Features


- Multi-threaded handling of client connections.

- Responds to HTTP GET requests with a simple message.

- Returns a "400 Bad Request" response for unsupported requests.


## Requirements


- Windows operating system.

- A C compiler that supports Winsock2 (e.g., GCC).
