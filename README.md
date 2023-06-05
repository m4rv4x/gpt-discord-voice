# GPT Discord Voice Bot (Legit Bot)
Simple Discord Voice Bot proof of concept  
GPT4 + ElevenLabs | google TTS -> Discord Voice Bot  

  
# Install Notes
debian:  


```
### Clone Rep
git clone https://github.com/m4rv4x/gpt-discord-voice
cd gpt-discord-voice

### Install Req
sudo apt install ffmpeg python3-pyaudio libportaudio2  
pip install -r requirements.txt

```
# Config
config.py
```py
### OPEN AI CHAT GPT CONFIG
openai.api_key = "OPENAI API Key"
openai.role = "Persona of AI"
openai.model = "gpt-3.5-turbo"

### TEXT TO VOICE API
elevenlabs_api_key = "Elevenlabs API Key"

### DISCORD BOT API
discord_api_token = 'Your Discord Bot Token'
discord_target_channel_id = your_voice_channel_num

### OPTIONS
tts_provider = "elevenlabs"

### USAGE 
prefix = "!"
name = "gpt"
```


### Run Bot
```
python3 bot.py & python3 voiceproxy.py
```
# Todo
Todo:
    Change needed to await async calls in discord properly
    
## Credits to Danomation  
    GitHub: https://github.com/danomation  
    Personal Site: https://sussyvr.com  
