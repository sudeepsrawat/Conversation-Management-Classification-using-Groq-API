# Conversation-Management-Classification-using-Groq-API

This project implements two core tasks using Groq APIs with OpenAI SDK compatibility:
1. Conversation history management with summarization
2. JSON schema classification and information extraction

## Features

### Task 1: Conversation Management with Summarization
- Maintain running conversation history
- Summarize conversation history to keep it concise
- Customizable truncation options:
  - Limit by number of conversation turns
  - Limit by character length
- Periodic summarization after every k-th run
- Demonstration with multiple conversation samples

### Task 2: JSON Schema Classification & Information Extraction
- Extract 5 details from chats (name, email, phone, location, age)
- Use OpenAI function calling with Groq API
- Validate outputs against the schema
- Parse multiple sample chats

## Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/conversation-management-groq.git
cd conversation-management-groq
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Set up your Groq API key:
* Get an API key from https://console.groq.com/
* Replace the placeholder in the notebook with your actual key

## Usage
Open the Jupyter notebook:
```bash
jupyter notebook notebooks/Conversation_Management_Classification.ipynb
```
Or run it in Google Colab by uploading the notebook.

## Requirements
* Python 3.8+
* Groq API key
* Libraries: groq, openai, python-dotenv
