# piCAMTracker
This is another Raspberry Pi motion tracker based on Python, picamera and opencv.   
It makes heavily use of the motion blocks generated by GPU of ther Raspbery Pi.   
**Target** A crossing event is detected on a GPIO port and a picture of the event is transmitted via nginxi to a smart phone for example.
# Prerequisites
* picamera
* opencv
* pygame
* libh264decoder
# Status
Currently this is an alpha release.   
* The object detection is working quiet well in different light conditions. It still needs some improvements.
* The web interface supports the most rudimentary stuff to control the camera.
# TODO
* Next phase is a testing phase. (Until now the system has been tested in the office only)
* Develop a setup script to enable other testers to use the software
* Save the stream and develope a debugging facility to improve the detection.
* Add a pull request to libh264decoder (I am using a patched version)
* if possible to encode/decode h264 at the same time then get rid of libh264decoder