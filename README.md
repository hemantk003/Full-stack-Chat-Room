## 🚀 Project Overview

This project demonstrates how to:

- Build a **chat application** with **real-time messaging**
- Use **Spring Boot** as the backend framework
- Integrate **WebSockets** for live communication between clients
- Serve dynamic UI with **Thymeleaf**
- Structure the app with best practices for scalability

---

## 🧱 Features

✅ Real-time message broadcasting  
✅ WebSocket connection handling  
✅ Simple UI using Thymeleaf  
✅ Spring Boot backend powered by WebSockets  
✅ Session-aware messaging  

---

## 📁 Project Structure

chat-app/

├── src/

│ ├── main/

│ │ ├── java/

│ │ │ └── com/example/chat/

│ │ │ ├── config/ # WebSocket configuration

│ │ │ ├── controller/ # Message handling

│ │ │ └── model/ # Message payload classes

│ │ └── resources/

│ │ ├── templates/ # Thymeleaf HTML files

│ │ └── application.yml # App configs

├── .gitignore

├── mvnw / mvnw.cmd

├── pom.xml # Maven dependencies

└── README.md

---

## 🛠 Prerequisites

Make sure you have installed:

- Java JDK 17+  
- Maven  
- Your favorite IDE (IntelliJ / VS Code / Eclipse)

---

## 🏃‍♂️ Running the App

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/chat-app.git
Navigate into the project:

cd chat-app
Build and run with Maven:

mvn spring-boot:run
Open in browser:

http://localhost:8080/chat
You should now be able to send and receive live chat messages! 🎉

📝 How It Works
This tutorial app uses:

WebSockets to establish persistent connections between client and server

Spring Boot for handling endpoints and message routing

Thymeleaf as the server-rendered HTML view engine

The WebSocket config enables a “/chat” endpoint that pushes messages to all connected users.

📦 Dependencies
Configured in pom.xml (Maven project):

spring-boot-starter-web

spring-boot-starter-websocket

spring-boot-starter-thymeleaf

