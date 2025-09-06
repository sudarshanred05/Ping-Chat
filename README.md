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
![WhatsApp Image 2025-09-06 at 16 37 32_4a059d69](https://github.com/user-attachments/assets/14965fc9-fd3d-4ef9-a175-df9ab757d0c6)


### 📝 Register Page
![WhatsApp Image 2025-09-06 at 16 37 49_004fede2](https://github.com/user-attachments/assets/68f2f433-6052-4520-97f1-8619f070f084)


### 👥 Contacts List
![WhatsApp Image 2025-09-06 at 16 38 09_26e68b75](https://github.com/user-attachments/assets/cecdc17d-cca5-4db2-9856-273e67729e02)


### 💬 Chat Window
![WhatsApp Image 2025-09-06 at 16 40 11_cc9e33b7](https://github.com/user-attachments/assets/bbc09651-e042-417a-98e9-bcc7553abbc1)


### 😀 Emoji Picker
![WhatsApp Image 2025-09-06 at 16 40 54_f4fb1e8a](https://github.com/user-attachments/assets/93a69403-45fc-4d7e-8924-ac4203070dc5)


---

## ⚡ Tech Stack
- **Frontend:** React.js, Styled Components  
- **Backend:** Node.js, Express.js, Socket.io  
- **Database:** MongoDB  
- **Storage:** Cloudinary  

---
