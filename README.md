# Speech processing
Forked from https://github.com/Uberi/speech_recognition

A repository for Speech processing with python:
- Speech to Text
- Text to Speech
- Audio files
- Speech control of the MPD Client

## Dependencies
- PyAudio (pip3 install pyaudio, apt-get install portaudio19-dev)
- python-mpd2 (pip3 install python-mpd2)
- monotonic (pip3 install monotonic)
- spacy (pip3 install spacy)
- expiringdict (pip3 install expiringdict)

## Project Layout
<pre><code>
/audio
    audio_data.py
    audio_file.py
    audio_file_stream.py
    microphone.py
    recognizer.py

/configs
    configuration.json

/mpd
    mpd_connection.py

/resources
    supported_languages.py

/speech_control
    speech_to_text.py
    text_to_speech.py

LICENSE
main.py
README.md
setup.py
</pre></code>
