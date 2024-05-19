# Q&A Chatbot
## Overview
This project is a Q&A Chatbot application that utilizes Google's Gemini AI to process and answer questions based on input images and text prompts. The application is built using Streamlit for the web interface and the Google Generative AI library for the backend AI processing.

## Setup
### Prerequisites
Python 3.7+
Streamlit
Google Generative AI SDK
dotenv
Pillow

## Installation
### Clone the repository:

git clone https://github.com/yourusername/qa-chatbot.git
cd qa-chatbot

## Create and activate a virtual environment:

1. On macOS and Linux:

python3 -m venv venv
source venv/bin/activate

2. On Windows:

python -m venv venv
venv\Scripts\activate

### Install the required packages:

pip install -r requirements.txt
Create a .env file in the project root directory and add your Google API key:

GOOGLE_API_KEY=your_google_api_key

## Running the App
To run the application:

1.Open a terminal or command prompt.
2.Navigate to the project directory.
3.Run the Streamlit app:

streamlit run app.py

### Functionality
Once the application is running:

Input Prompt: Enter a text prompt in the provided input field.
Upload Image: Upload an image file (JPG, JPEG, PNG) for analysis.
Submit: Click the "Tell me about the image" button to process the input.
The application will:

1.Load and preprocess the uploaded image.
2.Use the Gemini AI model to generate a response based on the input prompt and image.
3.Display the AI's response on the web interface.