# GeminiChatBot
A lightweight terminal-based chatbot powered by Google's Gemini 2.0 Flash model. This bot interacts through natural language using Generative AI and provides concise responses.
## Features
-Uses Gemini 2.0 Flash via Google's Generative AI API.
-Custom safety settings and generation configurations.
-Supports continuous chat with maintained history.
-Clean, minimal terminal interface.

## Requirements
- Python 3.8+  
- Google Generative AI SDK  
- `python-dotenv` for managing environment variables  
## Setup
- Clone the Repository:
`git clone https://github.com/yourusername/GeminiChatBot.git
cd GeminiChatBot`  

- Install Dependencies:
`pip install -r requirements.txt`  

- Configure Environment Variables: Create a .env file in the root directory and add your Google API key:
`GOOGLE_API_KEY=your_api_key_here`  

- Run the bot:
`python GeminiChatBot.py`  
## Exit the Chat
Type `exit`, `quit`, or `bye` at any time to end the session.

## Config Changes
This is the configurations of the model:
`generation_config = {
    "temperature": 0,
    "top_p": 0.95,
    "top_k": 64,
    "max_output_tokens": 8192,
    "response_mime_type": "text/plain"`   
      
  Tweak the figures as per your needs.
    
