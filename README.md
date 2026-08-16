# 💬 MERN Chat Application

A real-time chat application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. The application allows users to create accounts, log in, and communicate with other users through a clean and responsive chat interface.

## 🚀 Features

* 🔐 User Registration & Login
* 🔑 Authentication and protected routes
* 💬 Real-time messaging
* 👤 User profiles
* 🟢 Online/offline user status
* 📱 Responsive chat interface
* 🔍 Search users
* 💾 Messages stored in MongoDB
* ⚡ Fast and dynamic React interface
* 🔒 Secure API communication
* 📡 Real-time communication using Socket.IO

## 🛠️ Technologies Used

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Socket.IO Client

### Backend

* Node.js
* Express.js
* Socket.IO
* REST API

### Database

* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Token)
* Password hashing with bcrypt

## 📂 Project Structure

```text
Chat-Website-Using-MERN/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   └── server.js
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── context/
│       ├── services/
│       ├── App.jsx
│       └── main.jsx
│
├── .gitignore
├── package.json
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-chat-app.git
cd your-chat-app
```

### 2. Install dependencies

Install frontend dependencies:

```bash
cd client
npm install
```

Install backend dependencies:

```bash
cd ../server
npm install
```

### 3. Configure environment variables

Create a `.env` file inside the `server` directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
```

Replace the values with your own configuration.

### 4. Run the backend

```bash
cd server
npm run dev
```

### 5. Run the frontend

Open another terminal:

```bash
cd client
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

## 🔄 How It Works

The application follows a client-server architecture.

```text
              ┌─────────────────┐
              │   React Client  │
              │    Frontend     │
              └────────┬────────┘
                       │
                HTTP / Socket.IO
                       │
                       ▼
              ┌─────────────────┐
              │ Express / Node  │
              │     Server      │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │    MongoDB      │
              │    Database     │
              └─────────────────┘
```

Users interact with the React frontend. The frontend communicates with the Node.js/Express backend through APIs, while **Socket.IO** handles real-time communication. User and message data are stored in MongoDB.

## 💡 Key Learning Outcomes

Through this project, I gained practical experience with:

* Building a full-stack application using the MERN stack
* Creating REST APIs with Express.js
* Connecting Node.js applications with MongoDB
* Implementing JWT-based authentication
* Password hashing and user security
* Managing application state in React
* Implementing real-time communication with Socket.IO
* Creating reusable React components
* Handling API requests and errors
* Designing a responsive user interface

## 🔮 Future Improvements

* 📎 File and image sharing
* 🎤 Voice messages
* 📹 Video calling
* 👥 Group chats
* 😊 Emoji support
* ✔️ Message read receipts
* ✏️ Edit and delete messages
* 🔔 Push notifications
* 🌙 Dark mode
* 📱 Improved mobile experience






## 👨‍💻 Author

**Shamim Ara Nipa**

* GitHub: `(https://github.com/ShamimNipa)`
* LinkedIn: `https://www.linkedin.com/in/shamim-ara10/`
## ⭐ Contributing

Contributions, issues, and feature requests are welcome.

If you find this project useful, consider giving it a ⭐ on GitHub.

## 📄 License

This project is licensed under the MIT License.
