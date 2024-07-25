# chatbot
A Streamlit app for interacting with a chatbot powered by OpenAI's language model and SentenceTransformers. Features include caching for frequent questions and dynamic responses from the language model. Easy to deploy and use locally or on Streamlit Cloud.
# Streamlit Chatbot App

This repository contains a Streamlit application that enables users to interact with a chatbot. The chatbot is powered by OpenAI’s language model and SentenceTransformers for handling user inputs and responses. It also uses a simple caching mechanism for frequently asked questions.

## Features

- **Chat Interface:** Users can send messages and receive responses from the chatbot.
- **Caching:** Frequently asked questions are pre-cached for quick responses.
- **Language Model Integration:** Uses OpenAI’s language model via LangChain for generating responses to less common queries.

## Installation

To run this application locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/streamlit-chatbot-app.git
   cd streamlit-chatbot-app
