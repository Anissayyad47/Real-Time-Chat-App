<<<<<<< HEAD
<h1 align="center">🔥AmazeTalk (MERN-Chat-App) - Live Demo:<a href="https://amaze-talk.web.app/" target="_blank"> visit 🔗</a> </h1>
<img src="./client/amazetalk/screenshot/main.png" alt="Image Alt Text" style="max-width: 100%; height: auto">

# Project Overview 📚:
Welcome to Amazetalk, a real-time chatting web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with Socket.IO for seamless real-time communication. This project aims to provide users with an intuitive platform to engage in instant messaging while leveraging modern web technologies.

# Features 🖼️:

## Secure Login & Registration with JWT ⚠️
- AmazeTalk offers secure login and registration with JWT token authentication. Users can optionally personalize their accounts with profile pictures, enhancing their experience on the platform.
<img src="./client/amazetalk/screenshot/login.jpg" alt="Secure Login & Registration with JWT" style="max-width: 100%; height: auto;">

## Real-Time User Status and Typing Indicators 🤙
- AmazeTalk shows real-time user online status and typing indicators in chat, enhancing interaction and communication on the platform.
<img src="./client/amazetalk/screenshot/onlineTyping.png" alt="Real-Time User Status and Typing Indicators" style="max-width: 100%; height: auto;">

## Group Chat 👨‍👩‍👦‍👦
- AmazeTalk allows users to create groups and engage in group chats, enabling seamless collaboration and communication among multiple users in real-time.
<img src="./client/amazetalk/screenshot/GroupChat.png" alt="Group Chat" style="max-width: 100%; height: auto;">

## Real-Time Notifications 🔔
- AmazeTalk provides instant notifications in real-time, keeping users updated on new messages for timely communication and engagement.
<img align="center" src="./client/amazetalk/screenshot/notifi.png" alt="Image Alt Text" style="width: auto; height: 400px;">

## Dark Mode 🌚
- AmazeTalk offers a sleek and modern dark mode option, providing users with a comfortable viewing experience in low-light environments and reducing eye strain during extended usage.
<img src="./client/amazetalk/screenshot/Screenshot 2024-02-11 141017.png" alt="Dark Mode" style="max-width: 100%; height: auto;">

## Responsive Mobile Design 📱
- AmazeTalk boasts a responsive mobile design, ensuring seamless access and usability across various devices and screen sizes. Users can enjoy the full functionality of the application on their smartphones or tablets, enhancing accessibility and convenience on the go.
<img src="./client/amazetalk/screenshot/Responsivedeisgn.png" alt="Responsive Mobile Design" style="max-width: 100%; height: auto;">

## Tech-Stack 💻:
### Frontend
- React.js
- Framer motion (for animations)
### Backend
- Node.js
- Express.js
### Database
- MongoDB
### Real-Time Communication
- Socket.IO
### Authentication
- JWT (JSON Web Tokens)

# Installation Setup 🧰

To run this project locally, you need to follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/vibhorarya12/AmazeTalk-MERN-CHAT-APP.git
````
### 2. Install Dependencies for Client
Navigate to the client folder
```bash
cd client/amazetalk
````
Install dependencies using npm:
```bash
npm install
````
### 3. Enviroment variables setup for client
Navigate
```bash
cd client/amazetalk
````
create a new .env file
```bash
 touch .env && echo REACT_APP_API_KEY=http://localhost:5000 > .env
````
### 4. Install Dependencies for Server
Navigate to the server folder
```bash
cd ../..
cd server
````
Install dependencies using npm
```bash
 npm install
````
### 5. Enviroment variables setup for server
within server directory create a new .env file
```bash
touch .env
````
open .env file and add these variables:
```bash
PORT = 5000
DATABASE = Your MongoDb atlas connection string here
JWT = Awz76234Screet@77
````
⚠️Note: for DATABASE variable a mongoDb atlas connection string is required . Please refer to https://www.mongodb.com/docs/guides/atlas/connection-string/

### 6. Run Server
start the server
```bash
npm start
````
### 7. Run Client Application
navigate to client directory
```bash
cd ../client/amazetalk
````
Start the React app:
```bash
npm start
````



















=======
# 💬 Real-Time Chat Application

A **real-time chatting web application** built using the **MERN stack** (**MongoDB**, **Express.js**, **React.js**, **Node.js**) along with **Socket.IO** for seamless, instant communication.  
This platform allows users to engage in **real-time messaging** with a responsive and modern interface.

---

## 🚀 Features
- ⚡ **Real-time messaging** powered by Socket.IO  
- 👥 **User authentication** (Signup/Login with JWT)  
- 💬 **One-on-one and group chats**  
- 📱 **Responsive UI** for mobile and desktop devices  
- 🔔 **Instant notifications** for new messages  
- 🌐 **RESTful APIs** for backend services  
- 🗄 **MongoDB Atlas** for cloud-based storage  

---

## 🛠 Tech Stack
| Technology | Purpose |
|-------------|---------|
| **React.js** | Frontend framework for building the user interface |
| **Node.js** | Backend runtime environment |
| **Express.js** | Server-side framework for APIs |
| **MongoDB** | NoSQL database for storing users and chat data |
| **Socket.IO** | Real-time, bidirectional event-based communication |
| **JWT** | Secure authentication and session management |
| **Tailwind CSS**  | Styling and responsive UI components |

---

## Project Screen Shot 
## Login / Sign up 
<img width="1920" height="1080" alt="Chat-App - Google Chrome 25-08-2025 16_17_44" src="https://github.com/user-attachments/assets/8ca5b908-6a83-4374-bc79-1a03dac3eac2" />
<img width="1920" height="1080" alt="Chat-App - Google Chrome 25-08-2025 16_17_48" src="https://github.com/user-attachments/assets/1ac82ca2-4548-4122-a32a-9a0568800934" />

## User Interafce 
<img width="1920" height="1080" alt="Chat-App - Google Chrome 25-08-2025 16_18_26" src="https://github.com/user-attachments/assets/4153287b-4c59-4037-bc0e-ec4ecc53bfec" />
<img width="1920" height="1080" alt="Chat-App - Google Chrome 25-08-2025 16_18_33" src="https://github.com/user-attachments/assets/9c841819-c304-4798-a0c1-32f15a2ef5e4" />

## Search other users and friends 
<img width="1920" height="1080" alt="Chat-App and 10 more pages - Personal - Microsoft​ Edge 25-08-2025 16_49_27" src="https://github.com/user-attachments/assets/d84467c1-15d1-40af-91c9-3f80c21e9e00" />
<img width="1920" height="1080" alt="Chat-App and 10 more pages - Personal - Microsoft​ Edge 25-08-2025 16_49_52" src="https://github.com/user-attachments/assets/3bcf9a9f-17fa-4eca-a6e7-f822b98a1763" />

## Create groups and your freidns and start chatting 

<img width="1920" height="1080" alt="Chat-App and 8 more pages - Personal - Microsoft​ Edge 25-08-2025 18_26_26" src="https://github.com/user-attachments/assets/0e394d94-21b0-4525-848e-6801bd9316e6" />

<img width="1920" height="1080" alt="Chat-App and 10 more pages - Personal - Microsoft​ Edge 25-08-2025 16_20_00" src="https://github.com/user-attachments/assets/03c9ef80-d8a9-4750-8833-1109c5641cbb" />


<img width="1920" height="1080" alt="Chat-App and 10 more pages - Personal - Microsoft​ Edge 25-08-2025 16_20_12" src="https://github.com/user-attachments/assets/3b2cd268-c0c1-420b-840e-95531f541c5c" />



<img width="1920" height="1080" alt="Chat-App and 10 more pages - Personal - Microsoft​ Edge 25-08-2025 16_20_46" src="https://github.com/user-attachments/assets/37e27423-6688-46c7-83d3-93c5230102a9" />


<img width="1915" height="1023" alt="Screenshot 2025-08-25 174850" src="https://github.com/user-attachments/assets/0ce12996-11b1-4eaa-b8e3-e3e6915f2fc9" />

## Loading user interface 


<img width="1920" height="1080" alt="Chat-App and 10 more pages - Personal - Microsoft​ Edge 25-08-2025 16_34_32" src="https://github.com/user-attachments/assets/fc1a2064-3f93-43a1-bc67-42646c14dbd1" />
>>>>>>> 737ec5ca92dbc80844c9a2084675a538f88c303f


