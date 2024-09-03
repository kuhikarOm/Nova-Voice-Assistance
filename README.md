# Nova Voice Assistance

Nova is a virtual assistant, similar to Alexa and Google Assistant, capable of performing various tasks like opening websites, playing music, retrieving news, and responding to custom queries using OpenAI's GPT-3.5. This project is written in Python and utilizes several libraries to achieve its functionality.

## Features

- **Voice Recognition:** Listens and processes voice commands using `speech_recognition`.
- **Web Browsing:** Opens popular websites like Google, Facebook, YouTube, and LinkedIn.
- **Music Playback:** Plays songs by searching through a predefined music library.
- **News Updates:** Retrieves and reads out the latest headlines using the News API.
- **AI-Powered Responses:** Handles general queries using OpenAI's GPT-3.5-turbo model.
- **Text-to-Speech:** Converts text responses into speech using `gTTS` and `pygame`.

## Requirements

Before running the project, ensure you have the following Python modules installed:

- `speechrecognition`
- `webbrowser`
- `pyttsx3`
- `openai`
- `gtts`
- `pygame`

### Installation

   ```bash
   pip install speechrecognition pyttsx3 openai gtts pygame

