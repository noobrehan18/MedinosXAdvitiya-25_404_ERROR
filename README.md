# 🩺 CureConnect

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/noobrehan18/CureConnect)

## Problem Statement: Doctor Appointment Scheduling Assistant

Develop an intelligent, chatbot-driven system to streamline doctor consultations by:-

- **User Data Collection**: Gathering patient symptoms and preferred appointment times.
- **AI-Driven Doctor Matching**: Notifying doctors based on specialization, availability, and ratings.
- **Real-Time Notifications**: Providing instant consultation requests on doctors' dashboards.
- **Alternative Scheduling**: Suggesting available time slots if the preferred slot is unavailable.
- **Appointment Confirmation**: Confirming bookings and displaying details in the user's dashboard.
- **User Engagement**: Sharing medical facts during the booking process.



## Our Team:
***404_ERROR***

We are a dynamic group of coding enthusiasts from 🌎, passionate about exploring and mastering diverse technological stacks.

| Name          | Role                | GitHub Profile                                         |
|---------------|---------------------|--------------------------------------------------------|
| Md Rehan      | Frontend Developer  | [noobrehan18](https://github.com/noobrehan18)          |
| Binayak Panda | Backend Developer   | [batman-rises](https://github.com/batman-rises)        |
| Ashutosh Raj  | Frontend Developer  | [Ashu-Viron](https://github.com/Ashu-Viron)            |

## 📋 Table of Contents

- [Introduction](#introduction)
- [Overview](#overview)
- [Our Idea and Approach to Solve the Problem](#our-idea-and-approach-to-solve-the-problem)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#Contributing)

## 🌟 Introduction

**CureConnect** is an intelligent, chatbot-driven system designed to streamline the process of booking doctor consultations. It efficiently matches patients with the right healthcare professionals based on symptoms, availability, and doctor ratings, ensuring a seamless appointment scheduling experience.

## 📝 Overview

In today's fast-paced world, accessing timely and appropriate healthcare is crucial. Patients often face challenges in finding the right specialists, understanding their symptoms, and scheduling appointments that fit their busy lives. **CureConnect** addresses these challenges by providing a user-friendly platform that leverages artificial intelligence to connect patients with suitable doctors efficiently.

## 💡 Our Idea and Approach to Solve the Problem

At **CureConnect**, we aim to revolutionize the healthcare appointment process by leveraging advanced technology and user-centric design. Our approach focuses on creating a seamless experience for both patients and healthcare providers. Here's how we plan to achieve this:

1. **🤖 Intelligent Chatbot Interface**: 
   - **User-Friendly Interaction**: We have developed an intuitive chatbot that engages users in natural language conversations, making it easy to input symptoms and preferred appointment times.
   - **Efficient Data Collection**: The chatbot efficiently gathers necessary information, reducing the time and effort required from users.

2. **🧠 AI-Driven Doctor Matching**:
   - **Specialization Alignment**: Our AI analyzes user symptoms and matches them with doctors specializing in the relevant field.
   - **Availability Check**: It ensures that doctors are available during the user's preferred time slot.
   - **Rating Prioritization**: The system prioritizes doctors based on patient ratings, ensuring high-quality care.

3. **🔔 Real-Time Notifications**:
   - **Instant Alerts for Doctors**: Doctors receive immediate notifications about consultation requests on their dashboards, allowing for prompt responses.
   - **Efficient Scheduling**: This real-time communication streamlines the scheduling process, reducing delays.

4. **⏰ Alternative Time Slot Suggestions**:
   - **Proactive Solutions**: If no doctors are available at the requested time, the system proactively suggests alternative slots when doctors are available.
   - **Enhanced Flexibility**: This feature increases the chances of securing a convenient appointment time for users.

5. **✅ Appointment Confirmation**:
   - **Clear Communication**: Once an appointment is confirmed, all relevant details are provided to the user.
   - **Dashboard Integration**: The appointment information is seamlessly integrated into the "My Consultation" section of the user dashboard for easy access.

6. **🎉 Engaging User Experience**:
   - **Educational Insights**: To keep users engaged during the booking process, we display interesting medical facts and insights.
   - **Interactive Design**: The platform's interactive elements enhance user satisfaction and knowledge.

7. **💬📹 Diverse Consultation Options**:
   - **Multiple Channels**: Users can choose between video call and chat-based consultations, catering to different preferences and situations.
   - **Secure Communication**: Both options ensure secure access and allow for media sharing, facilitating comprehensive consultations.

8. **🕒 Post-Consultation Features**:
   - **Extended Access**: Users have access to the chat for up to 3 days after the appointment, enabling them to ask follow-up questions.
   - **Feedback Mechanism**: The platform encourages users to provide feedback and rate their doctors, contributing to continuous improvement.

By implementing these strategies, **CureConnect** strives to create a healthcare appointment system that is efficient, user-friendly, and beneficial for both patients and healthcare providers.

## 🚀 Features

- **User Information Collection** 📝: Gathers user symptoms and preferred appointment times through an intuitive chatbot interface.
- **AI-Driven Doctor Matching** 🤖: Notifies doctors based on specialization, availability, and rating hierarchy.
- **Real-Time Notifications** 🔔: Provides instant consultation requests on the doctor's dashboard.
- **Alternative Time Suggestions** ⏰: Suggests alternative slots if no doctors are available at the requested time.
- **Appointment Confirmation** ✅: Confirms appointments and displays details under "My Consultation" on the user dashboard.
- **Engaging User Experience** 🎉: Shares interesting medical facts during the booking process to keep users engaged.
- **Consultation Options** 💬📹: Offers both video call and chat-based consultations, with secure access and media sharing capabilities.
- **Post-Consultation Features** 🕒: Allows chat access for up to 3 days post-appointment and enables users to provide feedback and rate doctors.

## 🛠️ Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Frontend**: React.js, Tailwind CSS
- **Real-Time Communication**: Socket.io
- **Video Calling**: WebRTC / Google Meet API
- **AI Chatbot**: OpenAI API

## 🛠️ Installation

### Prerequisites

- Node.js (v14.x or higher)
- MongoDB
- npm (v6.x or higher)

### Backend Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/noobrehan18/CureConnect.git
   cd CureConnect/backend
2. **Install Dependencies:**
  ```bash
   npm install
```
3. **Configure environment variables:**
* Create a ```.env``` file in the ```backend``` directory.
* Add the following variables:
   ```bash
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
  ````
4. **Start the server:**
 ```bash
   npm start
 ```

### Frontend Setup
1.**Navigate to the frontend directory:**
   ```bash
   cd ../frontend
   ```
2. **Install dependencies:**
```bash
  npm install
   ```
3. **Configure environment variables:**
* Create a ```.env ```file in the ```frontend``` directory.
* Add the following variables:
   ```bash
   REACT_APP_API_URL=http://localhost:5000
  ````
4.**Start the Frontend Application:**
 ```bash
   npm start
 ```
# 🚀 Usage

## User Registration and Login

- **Sign Up**: Navigate to the registration page to create a new account.
- **Log In**: Use your credentials to log in to the platform.

## Booking a Consultation

1. **Interact with the Chatbot**: On the dashboard, initiate a conversation with the chatbot.
2. **Provide Symptoms**: Enter your symptoms and preferred appointment times.
3. **Receive Doctor Matches**: The system will suggest doctors based on your input.
4. **Confirm Appointment**: Select a doctor and confirm your appointment.

## Doctor Dashboard

- **View Notifications**: Doctors can view real-time consultation requests.
- **Manage Appointments**: Accept or decline appointments and view upcoming consultations.

## Post-Consultation

- **Chat Access**: Patients can access the chat for up to 3 days post-appointment for follow-up questions.
- **Provide Feedback**: Rate and provide feedback on the consultation experience.

# 🤝 Contributing to CureConnect

Thank you for considering contributing to CureConnect! Your involvement is greatly appreciated.

## How to Contribute

1. **Fork the Repository**: Click the "Fork" button at the top right of the [CureConnect GitHub repository](https://github.com/noobrehan18/CureConnect).

2. **Create a New Branch**:
   ```bash
   git checkout -b feature/YourFeatureName
    ```
3. **Make Your Changes**: Implement your feature or fix.
   
4. **Commit Your Changes**:
```bash
git commit -m 'Add feature: YourFeatureName'
```
5. **Push to Your Fork:**
  ```bash
git push origin feature/YourFeatureName
  ```
6. **Open a Pull Request**: Navigate to the original repository and open a pull request from your forked branch.
   
