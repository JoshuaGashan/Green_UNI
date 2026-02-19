# 🌿 GreenUNI - University Social Media Platform

Welcome to **GreenUNI**, a dynamic and interactive MERN stack platform designed to foster connections, communication, and collaboration among the vibrant community of our university. 

GreenUNI provides students, faculty, and staff with a centralized space for sharing, discovering, and engaging with all aspects of campus life—from academic updates to social opportunities.

---

## 🚀 Features

### 👤 User Roles & Interaction
* **Comprehensive Profiles:** Dedicated profiles for students and faculty to showcase academic interests.
* **Dynamic Feed:** Share updates, post images, and stay informed about campus activities in real-time.
* **Engagement Tools:** Like, comment, and interact with posts to build a stronger community.

### 🏛 Campus Life & Academics
* **Centralized Information:** A one-stop hub for academic announcements, exam schedules, and club activities.
* **Collaboration Spaces:** Discover and join study groups or social organizations across various departments.

### 🔒 Security & Navigation
* **JWT-Based Authentication:** Secure login system for both Admins and Users.
* **Role-Based Navigation:** Tailored interface and feature access based on your university role (Student/Staff/Admin).

---

## 🛠 Tech Stack

The application is built using the **MERN Stack**:

| Layer | Technology |
| :--- | :--- |
| **Frontend** | **React.js** (Functional components & Hooks) |
| **Backend** | **Node.js** & **Express.js** |
| **Database** | **MongoDB** (NoSQL Database) |
| **Authentication** | **JWT** (JSON Web Tokens) & **Bcrypt.js** |

---

## 🏗 System Architecture



GreenUNI utilizes a decoupled architecture where the React frontend communicates with a RESTful API powered by Node.js and Express, ensuring high performance and scalability for campus-wide usage.

---

## 🚀 Setup & Installation

### 1. Prerequisites
* [Node.js](https://nodejs.org/) (v16 or higher)
* [MongoDB](https://www.mongodb.com/) (Atlas or local instance)

### 2. Backend Setup
```bash
cd backend
npm install
# Create a .env file with: MONGO_URI, JWT_SECRET, and PORT
npm start


###3. Frontend Setup
Bash
cd frontend
npm install
npm start


🎨 Future Enhancements
Real-time Messaging: Integration of Socket.io for instant peer-to-peer communication.
Marketplace: A dedicated section for students to trade used textbooks and university gear.
Alumni Portal: Connecting current students with graduates for career mentorship.


