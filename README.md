#Python Chat

Description
Python Chat is a real-time communication platform designed for users to engage in conversations, reminiscent of popular messaging apps like WhatsApp. This project demonstrates the fundamental relationship between a server and multiple clients within a chat application.

Key Features:

Server-Client Architecture: The project highlights the essential client-server model, emphasizing how clients rely on an active server to connect to the chat.
Simultaneous Connections: Python Chat supports multiple clients, enabling several users to connect concurrently and engage in real-time conversations.
Communication Protocols: Utilizing both TCP and UDP communication protocols, the application ensures efficient data transfer between clients and the server.
Multithreading: The ability to run multiple clients simultaneously is achieved through the use of threads, enhancing the chat's scalability.
Messaging: Users can connect, send messages to specific users, and broadcast messages to everyone in the chat.
File Access: Python Chat allows users to download files stored on the server, promoting easy access to shared resources.
User and File Lists: Users can retrieve lists of chat participants and available files within the current folder.
Acknowledgment Mechanism: To mitigate message loss or disruptions, an acknowledgment (ACK) mechanism confirms the successful delivery of messages.
Python Chat serves as a practical example of networked communication, showcasing how data flows between clients and a central server, ultimately creating a robust and functional chat application.


---

## Usage

### Running the Project

1. **Server Setup:** To initiate the chat, you must first run the server by executing the `server.py` file. Ensure that the server is up and running before proceeding to connect clients.

   ```bash
   python server.py
   ```

2. **Client Connection:** Each user/client will require a separate command prompt (cmd) window. For each client, open a new cmd window and execute the `client.py` file.

   ```bash
   python client.py
   ```

### Interacting with the Chat

- **Initial Connection:** To join the chat, use the following command in the client's cmd window, replacing `<your name>` with your chosen username:

   ```bash
   <connect>your name
   ```

- **Sending Messages:** To send messages or perform actions, enclose the action in triangular brackets, followed by the message or username (without spaces). For example:

   - Send a message to a specific user:
     ```bash
     <set_msg>username Hello, how are you?
     ```

   - Broadcast a message to everyone in the chat:
     ```bash
     <set_msg_all>Hello, everyone!
     ```

- **Downloading Files:** Users can access shared files on the server. Simply specify the file name within triangular brackets to initiate the download.

   ```bash
   <download>file.py
   ```

- **Listing Users and Files:** Retrieve lists of chat participants and available files in the current folder using the following commands:

   - List of Users:
     ```bash
     <get_users>
     ```

   - List of Files:
     ```bash
     <listfiles>
     ```

These instructions provide a step-by-step guide on how to run the server and clients and interact effectively within the chat environment.

--- 
