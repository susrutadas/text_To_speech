# text_To_speech
Code to implement text to speech using the Google Text to Speech API commonly known as gTTS API, to convert the text entered, into audio which can be saved as a mp3 file.

## Installation
To install the gTTS API, open terminal and write
```bash
pip install gTTS
```
##Usage
```python
import os
from gtts import gTTS
from IPython.display import Audio
tts = gTTS("Duct tape is like the force. There's a dark side and a light side, and it holds the Universe together!!")
tts.save("out.wav")
sound_file = "out.wav"
Audio(sound_file, autoplay=True)
```
