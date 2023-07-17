# Voice AI

Voice AI is a Python application that leverages the OpenAI's Whisper and GPT-3.5 APIs to convert speech into text and generate responses.

## Features

- Transcribes audio into text
- Generates human-like text using the OpenAI GPT-3.5 model
- Copies the AI response to clipboard

## Requirements

- Python 3.6+
- OpenAI Python v0.27.0+
- Packages: openai, pyaudio, pynput, clipboard, tkinter
- A microphone to record audio
- Install these packages using pip:
```pip install openai pyaudio pynput clipboard tkinter```

## Setup

1. Clone the repository or download the code.
2. Install the necessary Python packages if not already installed.
3. Run the script with the command `python your_script.py`, replacing `your_script.py` with the name of the Python file you have this script saved in.

## Usage

1. Start the application.
2. Enter your OpenAI API key in the "API Key" field.
3. Enter a system message for the GPT-3.5 API in the "System Message" field. This will act as a prompt to guide the AI's responses.
4. Set a push-to-talk key. This key will be used to start and stop recording. Make sure to choose a key that does not interfere with your system's hotkeys.
5. Click the "Start" button to start the application. Once started, the input fields and the start button will be disabled.
6. Press and hold the push-to-talk key to start recording. Release the key to stop recording.
7. The application will then transcribe the recorded audio into text using the Whisper API, and then generate a response using the GPT-3.5 API.
8. The transcript and the AI response will be displayed in the text area and the AI response will be copied to your clipboard.

## Disclaimer

This might not work
