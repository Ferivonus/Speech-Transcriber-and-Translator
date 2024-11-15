# Speech-Transcriber-and-Translator

A speech recognition and translation tool that transcribes Turkish audio to text and translates it to English. The transcriptions are displayed in a GUI and saved in a `.docx` document. This tool is powered by **Google Speech Recognition** and **Google Translate** APIs.

## Features

- **Speech Recognition**: Records audio from the microphone and transcribes Turkish speech to text.
- **Translation**: Translates the Turkish text to English using Google Translate.
- **GUI**: Displays transcriptions (both Turkish and English) in a scrolling text area.
- **Document Saving**: Saves transcriptions to a `.docx` file for later use.
- **Continuous Transcription**: The program continuously listens and transcribes until the user chooses to stop.

## Requirements

- Python 3.x
- Tkinter (for GUI)
- SpeechRecognition
- PyAudio
- googletrans (for translation)
- python-docx (for creating Word documents)

You can install the required packages by running:

```bash
pip install -r requirements.txt
Create a requirements.txt file with the following content:
```


## Usage

- **Start Transcription:** Click on the "Start Transcription" button to begin listening to your speech and transcribing it into Turkish text, followed by an English translation.


- **Save Transcriptions:** Click on the "Save Transcriptions" button to save the current transcriptions to a .docx file.


- **Stop Transcription:** The transcription will stop when the user presses the "Stop" button (implement this functionality as needed).
## How It Works

The program continuously listens for audio input via the microphone.
When audio is captured, it is transcribed into Turkish using the Google Speech Recognition API.
The Turkish text is translated to English using Google Translate.
Both Turkish and English transcriptions are displayed in the GUI and saved to a Word document with timestamps.

## Example
- Turkish: "Merhaba, nasılsınız?"
- English: "Hello, how are you?"