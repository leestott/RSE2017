# Python How Old Demo
PyGame app using Kinect + Face API
https://aka.ms/PyCon2017

This is a bit of code that uses a Kinect v2 [pykinect2](https://github.com/kinect/pykinect2) and the [Microsoft Cognitive Service Face API](https://azure.microsoft.com/en-us/services/cognitive-services/face/)

If you have a surfacebook and Kinectv2 see the following if the Kinectv2 device isnt working correctly https://support.microsoft.com/en-us/help/4032123/kinect-sensor-is-not-recognized-on-a-surface-book 

This demo is pretty easy to get running. It was built using
- Python 3.6, 32 bit.
- PyGame, pykinect2, projectoxford, opencv, numpy (just install via the Requirements.txt file)

There is some minimum configuration to get going.
In config.py set the face client key so you can use oxford APIs. you can get one of these keys from the [Microsoft Cognitive Service Face API](https://azure.microsoft.com/en-us/services/cognitive-services/face/)


Also, this demo does use the Kinect but I took some time to have a non-kinect mode. if USE_KINECT is set to false, the code just uses the default webcam. You won't get user tracking and chest logos, but it will allow you to try out the cognitive service APIs.

To Install the prerequirements simply run the following command 

pip install -r requirements.txt

if you have python 2 and 3 installed then you to run pip3

pip3 install -r requirements.txt