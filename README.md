#Py-GSR
Simple way to access google api for speech recognition with python

#Dependencies
* **sox** - `apt-get install sox`
* **pyaudio** - `apt-get install python-pyaudio`

#Install
`pip install pygsr`

#Example
```python
from pygsr import Pygsr
speech = Pygsr()
speech.record(3) # duration in seconds (3)
phrase, complete_response = speech.speech_to_text('es_ES') # select the language
print phrase
```



