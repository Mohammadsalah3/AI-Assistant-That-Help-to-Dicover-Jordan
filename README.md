# Discover Jordan – AI Travel Assistant 🇯🇴🤖

Discover Jordan is an AI-powered web application that helps users explore tourist destinations in Jordan through an interactive chatbot.  
The system combines **chatbot conversation**, **image generation**, and **text-to-speech (TTS)** in one unified interface to provide a rich and engaging user experience.

---

## 🚀 Features

- **AI Chatbot**
  - Conversational assistant that answers user questions about tourist destinations in Jordan (e.g., Petra).
  - Supports function calling to retrieve ticket prices and destination details.
  
- **Image Generation**
  - Automatically generates an image related to the selected destination.
  - Enhances visualization and user engagement.

- **Text-to-Speech (TTS)**
  - Converts the chatbot’s text response into audio.
  - Allows users to listen to responses instead of reading.

- **SQLite Database**
  - Stores destination data such as cities and ticket prices.
  - Lightweight and easy to manage using the `sqlite3` library.

- **Web Interface**
  - Built with **Gradio** for a clean and interactive UI.
  - Displays chat, generated images, and audio output in one screen.

---

## 🧠 Technologies Used

- **Python**
- **OpenAI API**
  - Chat Completions
  - Function Calling
- **SQLite (sqlite3)**
- **Gradio**
- **Pillow (PIL)** – for image handling
- **JSON**
