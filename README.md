# 🔐 Password Manager

A **simple and secure Password Manager** built with **Node.js, Express, MongoDB, and Mongoose**.  
Easily store, manage, and retrieve your passwords while keeping them safe and organized.  

---

## ✨ Features

- 🔒 **Secure Password Storage** – Keep all your passwords encrypted and safe.  
- 🛡️ **User Authentication & Authorization** – Only authorized users can access their data.  
- 📱 **Responsive UI** – Mobile-friendly and intuitive interface built with Tailwind CSS.  
- 🔄 **Real-time Development Updates** – Automatic server restarts with Nodemon.  

---

## 🛠️ Technologies Used

| **Category**          | **Technology / Library**     | **Purpose**                                  |
|----------------------|-----------------------------|---------------------------------------------|
| Frontend             | HTML, CSS, Tailwind CSS      | Build responsive and modern user interface |
| Backend              | Node.js, Express             | Server and API logic                        |
| Database             | MongoDB, Mongoose            | Store and manage user credentials securely |
| Development Tools    | Nodemon                      | Automatic server reloads during development|

---

## 📦 Installation and Setup

Follow these steps to run the project locally:

### Prerequisites

- **Node.js** (v14 or later)  
- **MongoDB** (local or cloud instance)  
- **Git**

### Steps to Install
```bash
1️⃣ **Clone the repository**

git clone https://github.com/YOUR_GITHUB_USERNAME/password-manager.git
cd password-manager
2️⃣ Install dependencies

npm install


3️⃣ Configure environment variables

Create a .env file in the root directory:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000


4️⃣ Run the application

# Development mode
npm run dev

# Production mode
npm start
```

---

## 🔮 Future Improvements

🔐 Password Encryption – Implement AES or bcrypt encryption for added security.

📊 Analytics Dashboard – Show stats like most-used passwords or last access.

🔗 Browser Extension – Autofill passwords directly from the browser.

🌐 Cloud Sync – Sync passwords across devices securely.

---
