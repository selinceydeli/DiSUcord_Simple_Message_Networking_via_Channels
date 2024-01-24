# DiSUcord: Simple Message Networking via Channels

## Overview
DiSUcord is a message networking application designed for a Computer Networks course project. It facilitates communication through predefined channels, with the functionality of subscribing/unsubscribing to channels and sending/receiving messages. The project is divided into two main components: the Server and the Client, each managed via its graphical user interface (GUI).

### Features
- **Client-Server Architecture:** Connect multiple clients to a central server.
- **Channel Subscriptions:** Subscribe/unsubscribe to specific channels for messaging.
- **Unique Usernames:** User identification through unique usernames.
- **Real-time Messaging:** Send and receive messages instantly within subscribed channels.
- **GUI for Interaction:** Easy-to-use graphical interfaces for both server and client sides.

## Installation

### Prerequisites
- Visual Studio 2022 or later
- .NET Framework (compatible with Visual Studio 2022)
- Basic understanding of C# and TCP/IP networking

### Getting Started
1. **Download the Repository:**
   - Clone or download this repository to your local machine.

2. **Extract Files:**
   - There are two separate ZIP files for the server and client.
   - Extract these ZIP files to a preferred location on your system.

3. **Open Solution in Visual Studio:**
   - Navigate to the extracted folder.
   - Open the `.sln` (solution) file using Visual Studio 2022.

4. **Build the Project:**
   - Use the build option in Visual Studio to compile the project.

5. **Run the Server and Client:**
   - Start the server application first.
   - Then, run one or more instances of the client application.

### Configurations
- **Server Port Configuration:** Enter the port number in the server GUI to start listening for clients.
- **Client Setup:** Enter the server's IP address and port number in the client GUI to connect.

## Usage

### Server GUI
- **Start Listening:** Begin by entering the port number and initiating the server.
- **Monitor Activities:** View client connections, channel subscriptions, message logs, and disconnections.
- **Client Management:** Keep track of currently connected clients and their channel subscriptions.

### Client GUI
- **Connection Setup:** Enter server IP and port, and set a unique username to connect.
- **Channel Interaction:** Subscribe/unsubscribe to/from channels "IF 100" and "SPS 101".
- **Messaging:** Send and receive messages within subscribed channels.
- **Session Management:** Connect and disconnect from the server as needed.

## Project Structure

- **Server Module:** Manages client connections, subscriptions, and message multicasting.
- **Client Module:** Handles user interactions, message sending, and channel subscriptions.

## Limitations

- **No Authentication:** The system uses only usernames without passwords or additional security measures.
- **Local Network:** Primarily designed for local network communication.
- **Fixed Channels:** Only two pre-defined channels are available.

## Contact

For any queries or further assistance, please contact the repository owner.

---

**Note**: This README provides a comprehensive guide for installing, configuring, and using the DiSUcord application. It is crucial to follow the steps accurately for a successful setup and operation.
