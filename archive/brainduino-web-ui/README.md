On Collaboration Station
========================
In a terminal
```
$ source ~/pyvenv/brainduino/bin/activate
$ cd ~/brainduino/brainduino-web-ui
$ sudo env "PATH=$PATH" python main.py
```
Navigate to file:///home/noisebridge/brainduino/brainduino-web-ui/ws.html in a web browser. The current version of our ws.js (our simple Javascript) logs the brainduino data sent over the websocket to the browser console.

Setup
=====
* Requires Python 3.5+
* Depends on websockets and pyserial libraries



Setup for EEG reading instrument
Steps to recreate variance with 3d modeling a-frame: 
 - Connect to Bluetooth
 - run main.py
 - run web page file:///home/noisebridge/brainduino/brainduino-web-ui/webxr1.html
