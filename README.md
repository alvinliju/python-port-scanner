# Port Scanner

## Overview
This Python script is a simple port scanner that allows you to check if a specific port on a given IP address is open or closed. It utilizes the `socket` module in Python to establish connections with the specified IP address and port.

## How It Works
The port scanner script follows these steps:
1. Imports the `socket` module.
2. Prompts the user to enter the IP address and port number they want to scan.
3. Creates a TCP socket using `socket.socket()`.
4. Tries to establish a connection to the specified IP address and port using `socket.connect_ex()`.
5. Checks the return value of `socket.connect_ex()`. If the return value is non-zero, the port is considered closed; otherwise, it's considered open.
6. Prints the result indicating whether the port is open or closed.

## What I Learned
In the process of developing this port scanner, I learned the following:
- How to use the `socket` module in Python for network programming.
- How to create TCP sockets and establish connections with remote hosts.
- How to handle errors and exceptions, such as when a connection attempt fails.
- How to prompt users for input and process their responses in a Python script.

## Usage
1. Clone or download the repository.
2. Navigate to the directory containing the `main.py` file.
3. Run the script using Python 3:
    ```
    python3 main.py
    ```
4. Follow the prompts to enter the IP address and port number you want to scan.
5. The script will then display whether the specified port is open or closed.
