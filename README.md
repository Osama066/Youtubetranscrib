# Youtubetranscrib
# YouTube Transcript to Detailed Notes Converter

This is a Streamlit web application that takes a YouTube video link as input, extracts its transcript, and generates detailed notes summarizing the video content using Google Gemini Pro.

## Getting Started

1. Install the required packages:
   ```bash
   pip install streamlit python-dotenv google-generativeai youtube-transcript-api
Set up your Google API key:

Create a .env file in the root directory of your project.
Add your Google API key to the .env file

GOOGLE_API_KEY=your_api_key_here
streamlit run app.py

Usage
Enter the YouTube video link in the provided text input.
Click on the "Get Detailed Notes" button.
The application will extract the transcript of the video and generate detailed notes summarizing the content.


![Image Description](path/to/image.png)
