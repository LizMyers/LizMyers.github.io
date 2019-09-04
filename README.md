# Tensorflow

### AIY Voice Kit 

#### What is That?
Adding Vision to the Voice kit
This project adds computer vision to the voice kit so that the machine can describe what it sees. Using a Raspberry Pi, Tensorflow, and Python, you can identify three classes: logos, text, and objects. A detailed tutorial is available <a href="https://www.hackster.io/elizmyers/add-vision-to-the-aiy-voice-kit-e9ff3d" target="_blank">on Hackster.io</a>.


### TFJS - Experiments in Chrome

#### TFJS01
This project use the MobileNet Model for image recognition and the YouTube API for video control. In this example, the user trains the model on four gestures or poses that correspond to four video actions: play, pause, unmute, mute. While the program runs the webcam is watching for one of the poses and responds with the corresponding action.

#### TFJS02
The first version utilised standard video control buttons for training. In a quick usability test, I discovered that this caused friction and frustration because they were deceiving. They looked like real playback controls, but during inference they didn't do anything. Once Tensorflow kicks in... the only way to play/pause the video is with the corresponding gesture defined in training. 

Here's what I did to improve the usability: 
1. Separated training and inference areas (bottom and top rows respectively)
2. Implemented icons as labels rather than buttons (greyed out, single state)
3. Added still images on capture - reminding users of gestures and related actions

