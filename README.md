# Client-Server-Chat-Application_Project-Using-Java

## 📌 Overview


  This project is a **Java-based peer-to-peer chat application** that enables real-time **text-based communication** between users using **Java Socket Programming**.
  The Application is platform and architecture independent.

---
## ✨ Features


- Two-way communication between **client** and **server**.  
- Built on **TCP socket communication** for reliability.  
- Simple **console interface** for easy use.  
- Terminate session gracefully by typing `end`.  

---
## 🛠 Prerequisites


- **Java JDK 8 or higher** 
- A terminal or IDE (Command Prompt, VS Code, Eclipse, IntelliJ, etc.).

---
## 🚀 How to Run

1. **Compile the programs**  
   ```bash
   javac ChatServer.java ChatClient.java

2. **Start the server** (in one terminal)
     ```bash
     java ChatServer.java
     
3.  **Start the client** (in another terminal)
     ```bash
     java ChatClient.java
     
4. **Chat in real-time**

   - Client types a message → Server receives and replies.
    
   - Server sends a response → Client displays it.
    
   - Type `end` on the client side to close the chat.
