# Whishper_Speech_to_text_web
Whisper_Speech_to_Text_Web is a web app that converts speech to text using OpenAI’s Whisper model. Built with Gradio, it lets users record or upload audio and get accurate transcriptions instantly.


Features

🎙️ Record voice from the microphone

📂 Upload audio files (.wav, .mp3, etc.)

🤖 High-accuracy transcription using Whisper large-v3

🌐 Simple and interactive web interface

⚡ Supports GPU acceleration for faster processing

Tech Stack

  Python

  PyTorch

  Hugging Face Transformers (Whisper model)

  Gradio (Web UI)

  SoundFile (Audio processing)

Installation

Clone the repository:

  git clone <your-repo-link>
  cd Whisper_Speech_to_Text_Web


Install required packages:

  pip install torch torchvision torchaudio
  pip install transformers datasets accelerate soundfile gradio


(Optional) For local microphone recording on Linux/Mac:

# Linux
  sudo apt-get install portaudio19-dev
  pip install sounddevice
# Mac
  brew install portaudio
  pip install sounddevice

Usage

Run the app:

  python app.py


Web interface will open in your browser.

Record your voice or upload an audio file.

The app will process the audio using Whisper and display the transcription instantly.

How It Works

Audio Input – The user records or uploads audio.

Audio Processing – The audio file is read using soundfile.

Whisper ASR – The OpenAI Whisper large-v3 model transcribes the speech into text.

Display Output – Gradio shows the text in the browser interface.

Example

<img width="1366" height="768" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/056dcc0e-b6d5-4f95-9f6e-31dec8046369" />


Use Cases

Meeting and lecture transcription

Podcast and video content transcription

Accessibility for the hearing impaired

Hands-free note-taking

License

This project is open-source. Feel free to modify and use it for personal or educational purposes.
