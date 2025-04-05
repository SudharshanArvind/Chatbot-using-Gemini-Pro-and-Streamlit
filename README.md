# 🤖 Gemini Pro ChatBot

Welcome to the **Gemini Pro ChatBot**, a smart, conversational AI assistant powered by **Google Gemini-Pro** and wrapped in a sleek, intuitive **Streamlit UI**. This project demonstrates how to integrate state-of-the-art LLMs with a user-facing Python interface for real-time interaction.

---

## 📌 Table of Contents

- [🚀 Features](#-features)
- [🧰 Tech Stack](#-tech-stack)
- [⚙️ Setup Instructions](#-setup-instructions)
  - [1. Create a Virtual Environment](#1-create-a-virtual-environment)
  - [2. Install Dependencies](#2-install-dependencies)
  - [3. Configure Your API Key](#3-configure-your-api-key)
- [▶️ Run the App](#️-run-the-app)
- [📁 Project Structure](#-project-structure)
- [🛠️ Future Enhancements](#️-future-enhancements)
- [📄 License](#-license)
- [👤 Author](#-author)
- [🌟 Support & Feedback](#-support--feedback)

---

## 🚀 Features

✅ Powered by Google Gemini-Pro LLM  
✅ Streamlit-based chatbot interface  
✅ Secure API integration via `.env`  
✅ Live chat with session-based history  
✅ Simple, customizable, and production-friendly

---

## 🧰 Tech Stack

| Technology         | Role                                 |
|--------------------|--------------------------------------|
| Python             | Core scripting language              |
| Streamlit          | Frontend app interface               |
| Google Generative AI | LLM via `gemini-pro`                |
| python-dotenv      | Secure config via environment vars   |

---

## ⚙️ Setup Instructions

### 1. Create a Virtual Environment (Optional but Recommended)
Use a virtual environment to isolate dependencies:

```bash
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies
Install the required Python packages via:

```bash
pip install -r requirements.txt
```
|⚠️ If requirements.txt is not available, install manually:
```bash
pip install streamlit google-generativeai python-dotenv
```

---

### 3. Configure Your API Key
To use Gemini Pro, you need an API key from Google AI Studio:

Steps:
1. Go to **[Google AI Studio](https://makersuite.google.com/app/apikey)**

2. Generate your API key

3. Create a .env file in your root directory:
```ini
GOOGLE_API_KEY=your_actual_api_key_here
```
|🔐 Note: Keep your .env private. Never commit it to GitHub.

---

## ▶️ Run the App
Launch the chatbot locally using Streamlit:
```bash
streamlit run app.py
```
The app will start, and you’ll see a local URL (typically http://localhost:8501) in your terminal.

---

## 📁 Project Structure
```bash
gemini-chatbot/
│
├── app.py               # Main chatbot script
├── .env                 # Environment variables (keep secret)
├── requirements.txt     # All project dependencies
├── .gitignore           # Ignored files/folders
├── README.md            # You're reading it!
├── config.toml          # Optional Gemini config
└── credentials.toml     # Optional Gemini credentials
```

## 🛠️ Future Enhancements
 - Voice integration (speech-to-text)

 - Dark mode / theming

 - Download chat history

 - Persistent memory backend (via DB or session)

 - Modular API wrapper for plug-and-play LLMs

---

## 📄 License
This project is licensed under the MIT License — open source, free to use, modify, and distribute.

---

## 👤 Author
Sudharshan Arvind M
Artificial Intelligence & Data Science Enthusiast

📧 sudharshanarvind29@gmail.com

🔗 **[GitHub](https://github.com/SudharshanArvind)**

🌐 Reference - **[Youtube](https://www.youtube.com/watch?v=sf5MrM0AIiU&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6&index=38)**

---

## 🌟 Support & Feedback
If you found this project helpful, please ⭐ star the repo, fork it, and share your feedback through Issues or Pull Requests.

|“The future belongs to those who build with intelligence — one prompt at a time.” 💬
