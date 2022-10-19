# Video-Payer

This is a video player develped in python using PyQt5 package, object oriented programming and multi threading. It supports and can play all video formats. Unlike other video players, this application uses hand recognition to pause and play the video.

This video player runs a machine learning model to detect the hand in the camera feed and sends the appropriate commands to the video player to pause the video if the fist is opened and plays if closed.

This video player use vlc dependency to play all the video formats possible and opencv to receive the camera feed and sends it to the gesture detection model.

To execute the application, install all the dependencies using requirements.txt

# Packages used 

PyQt5.QtWidgets\
PyQt5.QtMultimedia\
PyQt5.QtMultimediaWidgets\
PyQt5.QtGui\
PyQt5.QtCore\
numpy\
mediapipe\
tensorflow.keras\
