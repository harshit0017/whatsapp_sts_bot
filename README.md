# whatsapp_sts_bot
send audio/text messages on whatsapp to twilio account get audio reply from chatgpt
# Things required to setup for this are twilio account , sandbox on twilio , ngrok, google cloud storage, openai api, any test to speech service(here we have used basic google tts), any speech to text service(we have used wishper model by openai).
#create a .env file in that store all the required api keys 
# api for openai , twilio sid, auth token
#install the required dependencies 
-- i will update the code with the requirements.txt file till then you can use the pip freeze command to proceed.
--also you need to host the audio online on public server so that twilio can access it, it does not take media from pvt hosts or local machines.
-- to run the program -->python run.py and start sending messages from your wp number to twilio registered number
 
