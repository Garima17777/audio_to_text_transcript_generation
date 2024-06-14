**Audio Transcription using AssemblyAI**

This Python script converts an audio file to WAV format and uses the AssemblyAI API to transcribe the audio to text. It then saves the transcription to a text file.

Getting Started
To use this script, you'll need to sign up for an account at AssemblyAI and obtain an API key.

Prerequisites
Python 3.x
Requests library (pip install requests)
Pydub library (pip install pydub)
Installation


**Clone the repository:**
pip install requests pydub
Replace 'Enter Your API Key' in the script with your actual AssemblyAI API key.

**Run the script:**
python audio_transcription.py

**Usage**
Convert your audio file to M4A format and save it as Sample_Audio.m4a in the same directory as the script.

Run the script. It will convert the audio file to WAV format, upload it to AssemblyAI, request a transcription, and save the transcription to a file named transcription.txt.

License
This project is licensed under the MIT License - see the LICENSE file for details.
