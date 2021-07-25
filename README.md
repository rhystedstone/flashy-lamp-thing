Flashy Lamp Thing
=================
### A fork of [Christian Scheb's Sound-To-Light-OSC](https://github.com/scheb/sound-to-light-osc), customised for remote GPIO in place of OSC.

"Real-time detection of beats with Python from an audio input device (typically 'Stereo Mix')"

[🎥 YouTube Livestream Involving This Project](https://www.youtube.com/watch?v=NwTgbfzS-9w)

![Image: The lamp that shall flash](lamp.png)
I received this lamp as apart of a secret santa and have loved it ever since. It's internal electronics are really simple, allowing me to do this project without risking the lamp (or my life I guess).

Notes
-----

- Built for use on Windows & Linux as I need this to run on a Raspberry Pi 4
- This project is tailored to my personal needs, therefore, there may be some weird code
- I'm not looking for contributors - this code may or may not be updated when it breaks, depending on if I need it or not
- The removal of OSC does sort-of kill the point of the original repo, however, I'm using remote GPIO as I'm using a Raspberry Pi 4 for light control and it's the easiest way to implement it

Required modules
----------------

- [PyAudio](https://pypi.org/project/PyAudio) (If installation fails, try installing [pipwin](https://pypi.org/project/pipwin) then using `pipwin install pyaudio`)
- [PyQt5](https://pypi.org/project/PyQt5)
- [matplotlib](https://pypi.org/project/matplotlib)
- [scipy](https://pypi.org/project/scipy)

Execution
---------
Simply run either from the commandline or directly

[**beatDetector.py**](beatDetector.py) - Runs normally, with console and GUI

[**beatDetectorNoConsole.pyw**](beatDetectorNoConsole.pyw) - Just runs with the GUI

Acknowledgments
---------------

Based on [scheb/python-beat-detector](https://github.com/scheb/sound-to-light-osc), which itself is based on [shunfu/python-beat-detector](https://github.com/shunfu/python-beat-detector)
