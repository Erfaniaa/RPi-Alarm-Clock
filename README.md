# RPi-Alarm-Clock
Raspberry Pi Alarm Clock, using a matrix keypad

A matrix keypad is something like this:

![matrix-keypad](https://user-images.githubusercontent.com/7780269/46922636-d9ff9b80-d018-11e8-9e1f-14ab2c12b9af.jpg)

## Usage
1. Config your Raspberry Pi time zone settings, and connect it to a speaker.
2. Clone this repository on your Raspberry Pi.
3.
```
pip install -r requirements.txt
```
4. Connect a matrix keypad to your Raspberry Pi, and config ROW_PINS and COL_PINS in the source code, according to your keypad connection pins.
5.
```
python RPiAlarm.py
```
6. Suppose that you want to set an alarm for 5:20 PM. Type *1720# with your keypad (*HHMM# format).
7. Wait until the supposed time (17:20) to hear the alarm sound.
