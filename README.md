# 📱 Ping Chat

Ping Chat is a MERN stack real-time chat application (similar to WhatsApp) that supports one-to-one messaging, media sharing, and secure authentication. It uses **React.js** for the frontend, **Node.js/Express** for the backend, **MongoDB** for the database, and **Cloudinary** for image storage.

---

## 🚀 Features
- 🔐 User authentication & authorization  
- 💬 Real-time one-to-one messaging (Socket.io)  
- 📷 Profile picture & media upload with Cloudinary  
- 🌙 Modern responsive UI  

---

## 🛠️ Setup Instructions

Follow the steps below to run the project locally.

### 1. Clone the repository
```bash
git clone https://github.com/sudarshanred05/Ping-Chat.git
cd Ping-Chat
```

---

### 2. Setup Client
```bash
cd client
npm install
npm start
```

This will start the frontend at `http://localhost:3000`.

---

### 3. Setup Server
Open a **new terminal** and run:
```bash
cd Ping-Chat
cd server
npm install
```

#### Create `.env` file inside `server/` directory:
```env
MONGO_URL=your_mongodb_connection_string
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
JWT_SECRET=your_jwt_secret
```

Then start the backend:
```bash
npm start
```

The backend will run on `http://localhost:5000`.

---

## 📂 Folder Structure
```
Ping-Chat/
│── client/      
│   └── src/assets/assets/assets/screenshots/   # Screenshots stored here
│── server/      
│── README.md
```

---

## 📸 Screenshots & Demo

### 🔐 Login Page
![Login](client/src/assets/assets/assets/screenshots/login.jpg)

### 📝 Register Page
![Register](client/src/assets/assets/assets/screenshots/register.jpg)

### 👥 Contacts List
![Contacts](client/src/assets/assets/assets/screenshots/contacts.jpg)

### 💬 Chat Window
![Chat](client/src/assets/assets/assets/screenshots/chat.jpg)

### 😀 Emoji Picker
![Emoji Picker](client/src/assets/assets/assets/screenshots/emoji.jpg)

---

## ⚡ Tech Stack
- **Frontend:** React.js, Styled Components  
- **Backend:** Node.js, Express.js, Socket.io  
- **Database:** MongoDB  
- **Storage:** Cloudinary  

---

## 🤝 Contribution
Contributions, issues, and feature requests are welcome!  
Feel free to fork this repo and submit pull requests.

---

## 📜 License
This project is licensed under the MIT License.
