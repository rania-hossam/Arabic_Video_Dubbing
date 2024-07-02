# Arabic Dubbing Demo

This project demonstrates an automatic dubbing pipeline that converts the audio of a video from English to Arabic. The `ArabicDubbing` class is designed to streamline the process of extracting audio from a video, transcribing it, translating the text, and then converting the translated text back to speech. The final product is an Arabic dubbed audio track that can be added back to the original video.

## Overview

The `ArabicDubbing` class automates the following steps:

1. **Extract Audio**: Extracts audio from the provided video file.
2. **Transcribe Audio**: Converts the extracted audio into text using a Speech-to-Text (whisper) model.
3. **Translate Text**: Translates the transcribed text from English to Arabic using a Llama3 model.
4. **Text-to-Speech**: Converts the translated Arabic text into speech using a Text-to-Speech (XTTS) model.
5. **Combine Audio Segments**: Combines all generated audio segments into a single audio file.



## Demo Video

[![Watch the video](https://img.youtube.com/vi/jZLYdPW68gg/maxresdefault.jpg)](https://youtu.be/jZLYdPW68gg)

Click the image above to watch the demo video on YouTube.



## Project Structure

The project consists of the following files:

```plaintext
ArabicDubbingDemo/
│
├── arabic_dubbing.py          # Implementation of the ArabicDubbing class
├── demo.py                    # Script to demonstrate the usage of the class
├── requirements.txt           # List of required dependencies
└── README.md                  # Project documentation



