# Tensorflow

### AIY Voice Kit 

#### What is That?
Adding Vision to the Voice kit
This project adds computer vision to the voice kit so that the machine can describe what it sees. Using a Raspberry Pi, Tensorflow, and Python, you can identify three kinds of things: logos, text, and objects. A detailed tutorial is available <a href="https://www.hackster.io/elizmyers/add-vision-to-the-aiy-voice-kit-e9ff3d" target="_blank">on Hackster.io</a>.


### TFJS - Experiments in Chrome

#### TFJS01
This project use the MobileNet Model for image recognition and the YouTube API for video control. In this example, the user trains the model on four gestures or poses that correspond to four video actions: play, pause, unmute, mute. While the program runs the webcam is watching for one of the poses and responds with the corresponding action.

#### TFJS02
The first version utilised standard video control buttons <em>as labels</em> and controls for training. In a quick usability test (with a friend), I discovered that this caused mental friction because the buttons didn't actually control the video. Once Tensorflow kicks in... the only way to play/pause the video is with the corresponding gesture defined in training. By clearly separating training and inference areas - as well as implementing <em>icons as labels - not as buttons</em>, version 02 has become more useable than v01.


