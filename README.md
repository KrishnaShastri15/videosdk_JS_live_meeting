# videosdk_JS_live_meeting

# VideoSDK JavaScript SDK Example

Welcome to the **VideoSDK JavaScript SDK Example** repository! This project demonstrates the use of VideoSDK's JavaScript SDK to build a feature-rich video conferencing application.

## 📚 Table of Contents

- [⚡ Quick Setup](#-quick-setup)
- [🔧 Prerequisites](#-prerequisites)
- [📦 Running the Sample App](#-running-the-sample-app)
- [🔥 Meeting Features](#-meeting-features)
- [🧠 Key Concepts](#-key-concepts)
- [🔑 Token Generation](#-token-generation)
- [📖 Examples](#-examples)
- [📝 VideoSDK's Documentation](#-videosdks-documentation)
- [💬 Join Our Community](#-join-our-community)

## ⚡ Quick Setup

1. **Sign up** on [VideoSDK](https://videosdk.live/) to get your API Key and Secret.
2. Familiarize yourself with the concept of tokens used for authentication and meeting management.

## 🔧 Prerequisites

Ensure the following are installed on your system:

- **Node.js** v12+
- **NPM** v6+ (comes pre-installed with newer Node versions)
- A valid **Video SDK Account**

## 📦 Running the Sample App

Follow these steps to set up and run the sample application:

### Step 1: Clone the Repository
```bash
git clone https://github.com/KrishnaShastri15/videosdk_JS_live_meeting.git
```

### Step 2: Set Up Environment Variables
Copy the example configuration file:
```bash
cp config.example.js config.js
```

### Step 3: Configure Your `config.js` File
Generate a temporary token from your [VideoSDK Account](https://videosdk.live/dashboard) and update the `config.js` file:
```javascript
TOKEN="Your Token Here"
```

### Step 4: Install Dependencies and Run the App
Install `live-server` globally and start the application:
```bash
npm install -g live-server
live-server --port=8000
```

Access the application in your browser at `http://localhost:8000`.

## 🔥 Meeting Features

This sample app includes the following features:

- Real-time audio and video communication.
- Dynamic participant management.
- Stream management for video and audio.

## 🧠 Key Concepts

### **Meeting**
A meeting represents real-time audio and video communication. (Note: Terms "Room" and "Meeting" are used interchangeably.)

### **Sessions**
The duration spent in a given meeting is called a session. Multiple sessions can exist for a specific `meetingId`.

### **Participant**
- **Local Participant**: Represents yourself (You).
- **Remote Participant**: Represents other attendees in the meeting.

### **Stream**
Refers to video or audio media content published by participants.

## 🔑 Token Generation

### Development Environment:
You can use a temporary token for development purposes. To generate one:
- Log in to the [VideoSDK Dashboard](https://videosdk.live/dashboard).
- Generate a temporary token.

### Production Environment:
For production use, you need to set up an authentication server to generate tokens securely. Refer to the [VideoSDK API Server Examples](https://github.com/videosdk-live/videosdk-rtc-api-server-examples) for guidance.

## 📖 Examples

Explore additional examples and use cases in the [official documentation](https://docs.videosdk.live/).

## 📝 VideoSDK's Documentation

Detailed documentation is available at [VideoSDK Documentation](https://docs.videosdk.live/).

## 💬 Join Our Community

Connect with us:
- [Discord Community](https://discord.gg/vedio-sdk)
- [GitHub Issues](https://github.com/videosdk-live/videosdk-rtc-javascript-sdk-example/issues)

---

Happy Coding with VideoSDK! 🚀
