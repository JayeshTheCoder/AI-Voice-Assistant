# Voice Assistant Model with LiveKit Integration

This project is a voice assistant model designed to process real-time audio streams using [LiveKit](https://livekit.io/). The assistant can listen to audio input, process it using natural language processing, and respond back with synthesized speech. This README outlines installation, setup, and usage.

## Features
- **Real-time Audio Processing**: Streams live audio to and from the assistant.
- **Natural Language Processing**: Supports a range of commands and conversational capabilities.
- **Audio Synthesis**: Responds with synthesized speech.
- **LiveKit Integration**: Uses LiveKit for real-time audio streaming and communication.

## Prerequisites

- **Python 3.12**
- **LiveKit API Key and Secret(Get this from [LiveKit](https://livekit.io/)->Settings->Keys)**
- **Get OpenAI API Key from [OpenAI](https://platform.openai.com/api-keys)**
  (You may need to enter your billing information to activate this feature. **Please note that this feature was free at the time I uploaded the project, but I cannot guarantee that it will remain free indefinitely**)
- **Change the name of sample.env to .env and add all the API Keys and Web URL to the desired locations in .env file**
-  **Use [Livekit Playground](https://agents-playground.livekit.io/#cam=1&mic=1&video=1&audio=1&chat=1&theme_color=violet) for launching the main.py app**
  ```bash
  python main.py start
```
### Required Libraries and Tools

To install required Python libraries:

```bash
pip install -r requirements.txt
