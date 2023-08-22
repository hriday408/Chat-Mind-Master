# ChatMind - A Real-Time Chat Application
---
ChatMind is a full stack chat application that allows users to communicate with each other in real-time. It supports features like user authentication, one-on-one chat, group chat, user profile management, and more.
 
### ⚙️ &nbsp; Time Taken in Completion of Project : 
---
 <p align="center">
<a href="https://wakatime.com/badge/user/f7838f29-ea5b-42c9-a473-628c7d8bc934/project/27f6a565-9c39-4922-8a4e-343c26e814d4"><img src="https://wakatime.com/badge/user/f7838f29-ea5b-42c9-a473-628c7d8bc934/project/27f6a565-9c39-4922-8a4e-343c26e814d4.svg" alt="wakatime"></a>
</p>
 
**Tech Stack:**

[![MERN Stack](https://img.shields.io/badge/Stack-MERN-61DAFB?style=flat-square)](https://en.wikipedia.org/wiki/MERN_(software_bundle))
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?style=flat-square)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/Backend-Express.js-000000?style=flat-square)](https://expressjs.com/)
[![React](https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?style=flat-square)](https://nodejs.org/)
[![Chakra UI](https://img.shields.io/badge/UI%20Framework-Chakra%20UI-319795?style=flat-square)](https://chakra-ui.com/)
[![CSS3](https://img.shields.io/badge/Styling-CSS3-1572B6?style=flat-square)](https://www.w3.org/Style/CSS/Overview.en.html)
[![Socket.IO](https://img.shields.io/badge/Web%20Sockets-Socket.IO-010101?style=flat-square)](https://socket.io/)

## Table of Contents 📜

 ## Demo 📸
![Demo](./gif/demo.gif)


## Table
- [Intro](#intro)
- [Sections](#sections)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [Setting Up .env in Backend](#setting-up-env-in-backend)
- [Hosting](#hosting)
- [Packages Used](#packages-used)
- [Upcoming Features](#upcoming-features)
- [Contribution Guidelines](#contribution-guidelines)

## Intro 📝

ChatMind is a chat application built with the MERN stack. It provides a seamless and real-time chatting experience for users. With features like user authentication, one-on-one chat, group chat, and user profile management, ChatMind offers a comprehensive solution for communication needs.

## Sections 🔖

- Home
  - Login Page
  - Sign Up Page
  - Forgot Password Page
- Chat Page
  - Search User
  - One-on-One Chat
  - Group Chat
  - User Profile
  - Group Menu





## Installation ⬇️

To run ChatMind locally, you will need to have Git and Node.js installed on your machine.

### Git

Download and install Git from the official website: [https://git-scm.com/downloads](https://git-scm.com/downloads)

### Node.js

Download and install Node.js from the official website: [https://nodejs.org](https://nodejs.org)

## Getting Started 🎯

To get started with ChatMind, follow these steps:

1. Fork and clone the repository from GitHub:
  
   ```bash
   git clone https://github.com/MehraDevesh2022/chat-mind.git
    ```


 ## Install the required packages for the backend by running the following command in the root directory:
 
   

    npm install 
    or 
    yarn add
  

## Install the required packages for the frontend by navigating to the frontend directory and running the following command:

  
    cd ./frontend 
    npm install
    or
    yarn add

## Run the backend server by running the following command in the root directory:
  
      npm start
      or
      yarn start

## Run the frontend server by navigating to the frontend directory and running the following command:
    
        cd ./frontend
        npm start
        or
        yarn start


        
    
## Folder Structure 📂

- backend
  - app.js
  - appUtils
    - error.js
    - jwtToken.js
  - controller
    - chatController.js
    - messageController.js
    - userController.js
  - db
    - connectDB.js
  - middleware
    - asyncWrapper.js
    - auth.js
    - errorHandler.js
  - model
    - ChatModel.js
    - MessageModel.js
    - UserModel.js
  - route
    - chatRoute.js
    - messageRoutes.js
    - userRoute.js
  - utils
    - .env
- frontend
  - build
    - asset-manifest.json
    - favicon.ico
    - index.html
    - logo192.png
    - logo512.png
    - manifest.json
    - robots.txt
  - public
    - favicon.ico
    - index.html
    - logo192.png
    - logo512.png
    - manifest.json
    - robots.txt
  - src
    - App.css
    - App.js
    - index.css
    - index.js
    - reportWebVitals.js 
  - animations 
    - typing.json 
  - components 
    - Chatbox.js 
    - ChatLoading.js 
    - EmojiOptions.js 
    - MyChats.js 
    - ScrollableChat.js 
    - SingleChat.js 
    - styles.css 
  - config 
    - ChatLogics.js 
  - Context 
    - ChatProvider.js 
  - img 
    - img.jpg 
  - Pages 
    - Chatpage.js 
    - Homepage.css 
    - Homepage.js

## Setting Up .env in Backend 🔧

To set up the environment variables for the backend, create a `.env` file inside the `backend/utils` directory with the following contents:

```bash

PORT=5000
DB_LINK=xxxx
JWT_SECRET=xxxx
JWT_EXPIRE=2d
COOKIE_EXPIRE=2
NODE_ENV=production
CLOUDINARY_NAME=xxxx
API_KEY=xxxx
API_SECRET=xxxx
CLOUDINARY_URL=xxxx

```





 
> Happy chatting with ChatMind! If you have any questions or need further assistance, feel free to reach out.
 




  
