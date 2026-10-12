
# Offline Chatbot

A simple offline chatbot built with Python, Streamlit, and Ollama. It provides a chat interface that allows users to interact with a locally running language model.

## Features

- Interactive chat interface built with Streamlit
- Local AI responses powered by Ollama
- Conversation history maintained during the Streamlit session
- Uses the Qwen 2.5 Coder 7B model
- Sends prompts to a locally hosted Ollama API
- Simple and beginner-friendly Python code

## Technologies Used

- Python
- Streamlit
- Requests
- Ollama
- Qwen 2.5 Coder 7B

## Project Structure

```text
Offline-Chatbot/
├── app.py
├── utils.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Requirements

- Python 3.10 or a compatible version
- Ollama installed on your computer
- The Qwen 2.5 Coder 7B model downloaded locally

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/mohammadazizi79/Offline-Chatbot.git
cd Offline-Chatbot
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate the virtual environment on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Install and prepare Ollama

Install Ollama from:

https://ollama.com/

Download the required model:

```bash
ollama pull qwen2.5-coder:7b
```

Make sure Ollama is running locally before starting the chatbot.

### 5. Run the application

```bash
streamlit run app.py
```

Streamlit will display a local URL in the terminal. Open that URL in your browser to use the chatbot.

## How It Works

The application uses Streamlit to display the chat interface and maintain conversation history during the session.

When a user submits a message, the application sends the prompt to the locally running Ollama API. Ollama generates a response using the selected language model, and Streamlit displays the result in the chat interface.

The model runs locally, so the application does not need a cloud-based AI API. However, the initial installation and model download require an internet connection.

## Notes

- Ollama must be running locally for the chatbot to generate responses.
- The default model is `qwen2.5-coder:7b`.
- The conversation history is stored in Streamlit session state and is not permanently saved.
- Model performance depends on your computer's hardware and available memory.
- This project is intended for learning and experimentation.

## Learning Goals

This project demonstrates how to:

- Build a basic chatbot interface with Streamlit
- Send HTTP requests using Python
- Connect Python applications to a local language model
- Manage chat messages with session state
- Organize application code into separate modules

## License

This project is available for educational and personal learning purposes.
