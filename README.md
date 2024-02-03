# WhatsApp_STS_Bot

WhatsApp_STS_Bot is a Python program that facilitates sending audio/text messages on WhatsApp to a Twilio account and receiving audio replies from ChatGPT.

## Prerequisites

Before using WhatsApp_STS_Bot, ensure you have the following:

- Twilio account
- Twilio Sandbox (for testing)
- Ngrok
- Google Cloud Storage account
- OpenAI API key
- Test to Speech service (Google TTS is used in this example)
- Speech to Text service (Whisper model by OpenAI is used here)

## Setup Instructions

1. **Create a `.env` file:**
   
   Create a `.env` file to store all the required API keys:

   ```env
   OPENAI_API_KEY=your_openai_api_key
   TWILIO_SID=your_twilio_sid
   TWILIO_AUTH_TOKEN=your_twilio_auth_token


2. Install the required dependencies:

```bash
pip install -r requirements.txt

Note: You can use pip freeze to generate the requirements.txt file if it's not provided.

Host the audio online:

Twilio requires audio to be hosted on a public server accessible via URL. Ensure your audio files are hosted online.

Run the program:

Execute the following command to run the program:

```bash
python run.py

Start sending messages from your WhatsApp number to the Twilio registered number.

#Additional Notes
Ensure that you update the code with the contents of the requirements.txt file when it becomes available.

Replace placeholders like your_openai_api_key, your_twilio_sid, and your_twilio_auth_token with your actual API keys.
