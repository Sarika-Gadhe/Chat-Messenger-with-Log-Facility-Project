# Client-Server-Chat-Application_Project-Using-Java

## 📌 Overview


  This project is a **Java-based Client-Server Chat Application** that demonstrates the fundamentals of **network programming**.  
  It enables a client and a server to communicate in real-time using **TCP sockets**, providing a simple console-based messaging system.  

## ✨ Features


- Two-way communication between **client** and **server**.  
- Built on **TCP socket communication** for reliability.  
- Simple **console interface** for easy use.  
- Terminate session gracefully by typing `end`.  

## 🛠 Prerequisites


- **Java JDK 8 or higher** 
- A terminal or IDE (Command Prompt, VS Code, Eclipse, IntelliJ, etc.).


## 🚀 How to Run

1. **Compile the programs**  
   ```bash
   javac ChatServer.java ChatClient.java

2. **Start the server** (in one terminal)
     ```bash
     java ChatServer
     
3.  **Start the client** (in another terminal)
     ```bash
     java ChatClient
     
4. **Chat in real-time**

   - Client types a message → Server receives and replies.
    
   - Server sends a response → Client displays it.
    
   - Type `end` on the client side to close the chat.
