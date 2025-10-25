Perfect 👌 — thanks for the clarification!
Here’s your **final, clean, and GitHub-optimized README.md** that reflects your actual folder structure:

---

# 📧 Email Reply Generator (Gemini API)

An AI-powered **Email Reply Generator** built using **Google Gemini API**.
This project features a **Chrome Extension** for Gmail integration, a **Vite + React frontend**, and a **Spring Boot backend** that communicates with the Gemini API to generate smart and professional email replies.

---

## 🚀 Features

* 🤖 AI-based email reply generation using Gemini API
* 🌐 Chrome Extension for Gmail or webmail integration
* ⚛️ Fast and modern frontend built with **Vite + React**
* ☕ Spring Boot backend for API processing and Gemini connection
* 🔒 Secure and modular architecture

---

## 🧠 How It Works

1. The **Chrome Extension** captures the selected email content from the user’s inbox.
2. It sends this content to the **Spring Boot backend** via REST API.
3. The backend calls the **Gemini API** to generate a professional reply.
4. The AI-generated reply is displayed inside the **extension popup** for quick editing or sending.

---

## 🧰 Tech Stack

| Component     | Technology                     |
| ------------- | ------------------------------ |
| **AI Model**  | Google Gemini API              |
| **Frontend**  | React + Vite                   |
| **Backend**   | Spring Boot (Java)             |
| **Extension** | Chrome Extension (Manifest v3) |

---

## 📁 Project Structure

```
email-reply-generator/
├── email-writer-extension/   # Chrome Extension (frontend + logic)
├── email-writer-sb/          # Spring Boot backend (Gemini API integration)
└── email-writer-react.zip    # Vite + React frontend (zipped folder)
```

---

## ⚙️ Setup Guide

### 🪄 1. Clone the Repository

```bash
git clone https://github.com/your-username/email-reply-generator.git
cd email-reply-generator
```

---

### ☕ 2. Backend Setup (Spring Boot)

1. Navigate to the backend folder:

   ```bash
   cd email-writer-sb
   ```
2. Change your Gemini API key in `application.properties`:

   ```properties
   GEMINI_API_KEY=your_gemini_api_key_here
   ```
3. Run the backend:

   ```bash
   mvn spring-boot:run
   ```

   Your backend will be running at **[http://localhost:8080](http://localhost:8080)**

---

### ⚛️ 3. Frontend Setup (Vite + React)

1. Unzip the `email-writer-react.zip` file.
2. Navigate into the extracted folder:

   ```bash
   cd email-writer-react
   ```
3. Install dependencies:

   ```bash
   npm install
   ```
4. Run the frontend:

   ```bash
   npm run dev
   ```

   Vite will start the app on **[http://localhost:5173](http://localhost:5173)**

---

### 🧩 4. Chrome Extension Setup

1. Open Chrome and visit **chrome://extensions/**
2. Enable **Developer Mode** (top-right toggle)
3. Click **Load Unpacked**
4. Select the `email-writer-extension/` folder
5. The extension connects to your backend at **[http://localhost:8080](http://localhost:8080)** to generate replies

---

## 💡 Future Enhancements

* ✨ Add tone options (formal, friendly, concise)
* 🌍 Support multiple languages
* 💌 Gmail API integration for direct sending
* 🎨 Improved extension UI and UX

---

## 🧾 License

This project is open-source and intended for learning and demonstration purposes.
Feel free to use, modify, or enhance it as you like! 💻

---

Would you like me to make this version **portfolio-ready** (with a short intro tagline, banner placeholder, and emoji header style for GitHub)? It’ll look even better on your repo homepage.
