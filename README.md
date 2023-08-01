# Video Audio Translator

This script translates the audio from any video in the directory of the script. It leverages OpenAI's Whisper API to provide accurate translations.

## Requirements

- Python 3.6 or above
- OpenAI Python package
- MoviePy package
- OpenAI API key

## Installation

1. Install the required packages:

   ```bash
   pip install openai moviepy
   ```

2. Replace the OpenAI API key in the script with your own:

   ```python
   openai.api_key = "YOUR-API-KEY-HERE"
   ```

## Usage

1. Place the video files you want to translate in the same directory as the script.
2. Run the script:

   ```bash
   python simplifiedtranslate.py
   ```

3. The translated audio will be saved in the same directory.

## Note

- Make sure to comply with OpenAI's terms and conditions when using the Whisper API.
- The script currently saves the translated audio as "Download_audio.wav". You may modify this in the code if required.

