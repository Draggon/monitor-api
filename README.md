This project uses https://github.com/rockowitz/ddcutil to turn an RPi (or something similar) into a “button” for switching the monitor input (on LG monitors, this needs to be done via the OSD, which is annoying)
The RPi is connected via HDMI and sends input-switching commands.
Currently, the RPi hosts a simple web page that allows selecting the input source.
Additionally, I am considering support for a physical button via the RPi’s GPIO.
In the future, I plan to add PIP support and a few other features.

My setup 
- RPi Zero 1/2 (W)
- Raspberry Pi OS Lite (no desktop)
- above code
- code that wraps above with service (to run it as start)

Prerequisite:
- python3 instaled
- ddcutil instaled
