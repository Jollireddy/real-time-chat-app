# Real-Time Chat Application

A modern real-time chat application built using **Java**, **Spring Boot**, **React**, and **MongoDB**. This project demonstrates real-time communication, user authentication, and a scalable backend, making it suitable for chat rooms, direct messages, and notifications.

## Table of Contents
- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Running the Application](#running-the-application)
- [Demo Link](#demo-link)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This **Real-Time Chat Application** allows users to:
- Register and authenticate via **JWT** (JSON Web Token).
- Send and receive messages instantly using **WebSockets**.
- Create and join **chat rooms** or send **direct messages**.
- View the **chat history** of messages.
- Receive **real-time notifications** for new messages.

The backend is built with **Spring Boot** and uses **MongoDB** to store user data and messages. The frontend is built using **React** and communicates with the backend through **WebSockets** and **RESTful APIs**.

## Technologies Used
- **Backend**:
  - **Java** & **Spring Boot**: For building RESTful APIs and WebSocket communication.
  - **JWT (JSON Web Token)**: For secure user authentication.
  - **MongoDB**: For storing messages and user data.

- **Frontend**:
  - **React**: For building the user interface.
  - **Socket.io-client**: For managing real-time communication via WebSockets.

- **Deployment**:
  - **Heroku**: For deploying the backend (Spring Boot).
  - **Netlify**: For deploying the frontend (React).

## Features
- **User Authentication**: Register and log in with JWT authentication.
- **Real-Time Messaging**: Instant message delivery via WebSocket.
- **Chat Rooms**: Create and join public or private chat rooms.
- **Direct Messaging**: Send one-on-one messages with other users.
- **Message History**: View previous messages in the chat room or direct messages.
- **Notifications**: Get notified when new messages are received.
- **Responsive UI**: Accessible across devices with a clean and responsive design.

## Setup Instructions

### Prerequisites
- Java 11 or above
- Node.js and npm
- MongoDB (local or cloud instance)

### Backend Setup (Spring Boot)
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/real-time-chat-app.git
   cd real-time-chat-app/backend
