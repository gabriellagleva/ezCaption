EZ Caption is a way to create fast and dirty open captions for live streaming. While not perfect, it serves as both a proof of concept, and an opprotunity for improvement

How does it work:

Audio is recorded using the pyaudio package. WHen the system determins the user is done talking, it will thing write the file do the disk, where fasterwhisper will transcribe the audio.
Then, pygame is used to show the subtitles.

Dependancies:
Pygame
FasterWhisper



Please note: That while it is compatible with OBS, it contains absolutly no code from the OBS project. As such, because all programs that can use chroma keys are compatible with ezCaption, it likely does not violate the terms of OBS' license, and can be licensed under the MIT license 
