# Java GUI Chatting Application

A simple GUI-based chatting application developed in Java, consisting of a server and a client. This application enables real-time text communication between two users over a network.

## Features

- **Server-Client Architecture**: The application consists of two files, one for the server and one for the client.
- **Real-Time Messaging**: Supports real-time chat between the server and client.
- **Graphical User Interface**: User-friendly GUI built using Java Swing for intuitive chat experience.

## Requirements

- Java Development Kit (JDK) 8 or higher

## How to Run

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/java-gui-chatting-app.git
    cd java-gui-chatting-app
    ```

2. **Compile the Code**:
    ```bash
    javac Server.java Client.java
    ```

3. **Run the Server**:
    ```bash
    java Server
    ```

4. **Run the Client**:
    ```bash
    java Client
    ```

5. **Start Chatting**: Once both the server and client applications are running, you can start chatting by typing messages into the client window.

## File Structure

- `Server.java`: Contains the server-side code to handle incoming connections and manage messages.
- `Client.java`: Contains the client-side code to connect to the server and send/receive messages.

## Future Enhancements

- Implement multi-client support.
- Add message history and saving feature.
- Enhance UI/UX with modern design elements.

## Contributing

Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License.
