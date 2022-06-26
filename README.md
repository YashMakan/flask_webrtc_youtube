flask_webrtc_youtube
================

A basic WebRTC video audio chat app made using python Flask.

Create and join video chat rooms. The users connects to each other in a peer to peer mesh network using WebRTC. They share their audio and video directly with each other without going through a centralized server. However, a centralized server is needed to initiate the connections at first using a process called signaling. This, signaling server is made using Flask in python and data is shared between server and clients using SocketIO.

[![YouTube Video: https://youtu.be/ZvG1-s7QmLs](https://img.youtube.com/vi/ZvG1-s7QmLs/0.jpg)](https://www.youtube.com/watch?v=ZvG1-s7QmLs)

For demo & explaination visit: https://youtu.be/ZvG1-s7QmLs

Installation
-------------
To run this on your machine, install the following:
#### Requirements:
* python 3.x
* Flask
* Flask-SocketIO

Install requirements using pip:
```
pip install -r requirements.txt
```

To start a server on localhost:
```
python server.py
```
