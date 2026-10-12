
# 🤖 Offline Chatbot

A local AI chatbot built with Python, Streamlit, and Ollama using the Qwen2.5-Coder 7B model.

The chatbot runs AI inference locally on your computer without requiring a paid external AI API.

## ✨ Features

- Interactive chat interface built with Streamlit
- Local AI responses powered by Ollama
- Uses the Qwen2.5-Coder 7B model
- Conversation history during the current session
- Simple and lightweight Python implementation

## 🛠️ Technologies

- Python
- Streamlit
- Requests
- Ollama
- Qwen2.5-Coder 7B

## 📁 Project Structure

```text
Offline-Chatbot/
├── src/
│   ├── app.py
│   └── utils.py
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Install Ollama

Download and install Ollama from its official website:

https://ollama.com/

### 2. Download the AI Model

Open a terminal and run:

```bash
ollama pull qwen2.5-coder:7b
```

### 3. Install Python Dependencies

Navigate to the project root directory and run:

```bash
pip install -r requirements.txt
```

### 4. Run the Application

From the project root directory, run:

```bash
streamlit run src/app.py
```

Streamlit will open the chatbot in your web browser.

## 📝 Notes

- Ollama must be installed and running locally.
- The Qwen2.5-Coder 7B model must be downloaded before use.
- An internet connection is required to download Ollama and the model initially.
- After setup, AI inference runs locally on your computer.
- The application uses Ollama's local API at `http://localhost:11434`.

## 👨‍💻 Author

**mohammadazizi79**

GitHub: https://github.com/mohammadazizi79
