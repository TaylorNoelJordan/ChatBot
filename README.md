# AI Chatbot

An interactive AI-powered chatbot built with **React, TypeScript, Node.js, and OpenAI's API**. This chatbot allows users to send messages and receive AI-generated responses in real time.

## 🚀 Features
- Real-time messaging interface
- AI-generated responses using OpenAI's GPT models
- Fully responsive UI built with React and TailwindCSS
- Backend API with Express.js

## 🛠️ Technologies Used
- **Frontend:** React, TypeScript, Vite, TailwindCSS
- **Backend:** Node.js, Express
- **AI Model:** OpenAI GPT-4o (or GPT-3.5-turbo as a fallback)
- **Environment Variables:** dotenv
- **Package Manager:** npm

---

## 📌 Installation & Setup

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### **2️⃣ Set Up Environment Variables**
Create a `.env` file in the root directory and add:
```sh
OPENAI_API_KEY=your_openai_api_key
PORT=5000
VITE_BACKEND_URL=http://localhost:5000
```

### **3️⃣ Install Dependencies**
Run the following command in both the frontend and backend folders:
```sh
npm install
```

### **4️⃣ Start the Backend Server**
```sh
cd backend
npm run dev
```

### **5️⃣ Start the Frontend**
```sh
cd frontend
npm run dev
```

---

## 🔥 Usage
1. Open the frontend in your browser (usually `http://localhost:5173`).
2. Type a message in the chat input box and press Enter.
3. The AI will generate a response based on your input.

---

## 📌 API Endpoints
### **POST /api/chat**
Sends user input to the OpenAI API and returns the AI response.
#### **Request Body:**
```json
{
  "message": "Hello, AI!"
}
```
#### **Response:**
```json
{
  "response": "Hello! How can I assist you today?"
}
```

---

## ✅ Future Enhancements
- Support for chat history
- User authentication
- Voice-to-text and text-to-speech integration
- Improved UI/UX design

---

## 🛠️ Troubleshooting
### **1️⃣ Port Already in Use Error**
If you see `EADDRINUSE: address already in use :::5000`, try killing the process:
```sh
npx kill-port 5000
```

### **2️⃣ OpenAI API Key Issues**
- If you get `model_not_found`, ensure you’re using the correct model (`gpt-4o` or `gpt-3.5-turbo`).
- If you see `quota exceeded`, check your usage at [OpenAI Billing](https://platform.openai.com/account/billing).

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

---

## 👥 Contributors
- **Taylor Jordan** - [GitHub Profile](https://github.com/TaylorNoelJordan)

