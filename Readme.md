# Buzzhub - A Complete MERN Stack Social Media Platform

Buzzhub is a fully functional social media platform built using the MERN stack. It features real-time chat functionality, a responsive design, and an intuitive user experience. This project utilizes MongoDB, Express, React, Node.js, and Socket.io.

---

## 🚀 Features

### 🔐 Authentication
- User registration and login
- Password encryption with salt for enhanced security

### 📢 Posts
- Create posts with text (caption) and images
- Like and delete posts
- Comment on posts
  - View all comments
  - Delete comments

### 💬 Messaging
- Real-time messaging with Socket.io
- Dark and light mode support
- Real-time typing indicators
- Search for chats
- Notifications for new messages

### 🔎 User Search & Suggestions
- Search for users by name or email with autocomplete
- User suggestions menu

### 👤 Profile Management
- View user details and posts
- Follow/Unfollow users
- Edit profile:
  - Change profile picture
  - Update email, password, and name
  - Add a personal bio

---

## 🛠️ Setup & Installation

### Prerequisites
Ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/) or [MongoDB Atlas](https://www.mongodb.com/atlas/database)
- [NPM](https://www.npmjs.com/)

### 🔧 Steps to Run the Application

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/buzzhub.git
   cd buzzhub
   ```

2. Configure environment variables:
   - Create a `.env` file in the root folder
   - Add your MongoDB connection string
   
3. Install backend dependencies:
   ```sh
   npm install
   ```

4. Start the backend server:
   ```sh
   node server
   ```

5. Install frontend dependencies:
   ```sh
   cd FrontEnd
   npm install
   ```

6. Start the frontend:
   ```sh
   npm start
   ```

---

## 📌 Additional Notes
- Ensure MongoDB is running locally or use MongoDB Atlas.
- The application is fully responsive and works across all devices.
- Built using modern web development practices for efficiency and scalability.

Happy Coding! 🚀

