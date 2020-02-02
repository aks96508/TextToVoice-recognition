# TextToVoice-recognition
from gtts import gTTS
import os

mytext="Welcome Mylove"
language="en"

myconv=gTTS(text=mytext,lang=language,slow=False)

myconv.save("Hello.mp3")
os.system("Hello.mp3")
