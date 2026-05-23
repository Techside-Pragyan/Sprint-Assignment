# 🧠 DocumentMind AI — Your Smart Document Assistant

> Stop reading long files. Upload any PDF, Word document, or image, and let smart AI explain, summarize, or answer questions about it instantly! 🚀

---

## ✨ What is DocumentMind AI?

**DocumentMind AI** is an intelligent, secure, and modern web application that acts as a personal assistant for all your reading. Instead of spending hours going through complex papers, reports, or images of text, you can simply upload them and have a natural, interactive conversation with the AI about their contents.

It reads **PDFs**, Microsoft **Word documents**, and even **images** (using advanced OCR text-scanning) to bring all your data into one unified chat interface.

---

## 🚀 Key Features

*   **📄 Smart PDF & Word Reader** — Upload your `.pdf` and `.docx` files, and watch the AI extract and understand the text in seconds.
*   **📷 Image-to-Text OCR scanner** — Have a screenshot, photo, or scanned document? The built-in scanner reads text directly from images.
*   **💬 Interactive AI Chat** — Chat naturally with your documents using powerful **AI models** to get summaries, explainers, or key insights.
*   **🔒 Secure User Accounts** — Created with custom registration, secure login password protection, and personal workspaces to keep your files private.
*   **🎨 Stunning Modern Interface** — A premium, responsive interface styled with Tailwind CSS, supporting seamless navigation.

---

## 🛠️ The Tech Stack

This project is built using a modern, scalable full-stack architecture:

### Frontend (The Interface)
*   **Framework:** Next.js (React) with TypeScript
*   **Styling:** Modern Tailwind CSS (v4) for a premium, fast, and responsive user experience

### Backend (The Brains)
*   **Server Framework:** Express (Node.js)
*   **Database:** MongoDB via Mongoose for saving users and document logs
*   **AI Engine:** Google Generative AI SDK (`@google/generative-ai`)
*   **File Parsers:** `pdf-parse` (for PDFs), `mammoth` (for Word), and `tesseract.js` (for Image OCR)
*   **Authentication:** JSON Web Tokens (JWT) for secure user sessions

---

## ⚙️ Quick Start Guide

Follow these steps to run the application locally on your machine.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Techside-Pragyan/Sprint-Assignment.git
cd Sprint-Assignment
```

### 2️⃣ Backend Setup (Server)
1. Go to the server directory:
   ```bash
   cd server
   ```
2. Install the backend dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `server` directory and add your environment variables:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   API_KEY=your_google_generative_ai_key
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### 3️⃣ Frontend Setup (Client)
1. In a new terminal window, navigate to the client directory:
   ```bash
   cd client
   ```
2. Install the frontend dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application! 🌟

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](file:///c:/Users/pragy/Documents/GitHub/Sprint-Assignment/LICENSE) file for more details.