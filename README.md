# Speech-Text
This project is a Google Colab-based application that:

1. Transcribes uploaded audio files (.wav or .mp3) into text using SpeechRecognition.

2. Cleans the text (adds capitalization & punctuation).

3. Checks grammar mistakes using LanguageTool.

4. Calculates an accuracy score for the transcription.

# Features
- Upload audio files in .wav or .mp3 format.

- Automatic speech-to-text transcription.

- Formatting: adds capitalization and punctuation.

- Grammar analysis & accuracy score.

- Suggestions for grammar corrections.

# Setup 

1. Open the notebook in Google Colab.

2. Install dependencies:
```bash
!pip install SpeechRecognition language-tool-python pydub
```

3. Run the code cell.

4. Upload an audio file when prompted.

# Tech Stack

-Python

-SpeechRecognition → for speech-to-text

-LanguageTool → for grammar checking

-pydub → for audio conversion (MP3 → WAV)

-Google Colab → execution environment
