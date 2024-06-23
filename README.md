OpenCV (Open Source Computer Vision Library) is an open-source software library designed for computer vision and machine learning applications. It offers tools and algorithms for image processing, video analysis, and object detection, among other tasks

SnapLens - Real-time Snap Glasses Application
SnapLens is a Python script that uses OpenCV and cvzone to detect faces in real-time from a webcam feed and overlay various glasses designs onto detected faces. It also detects blinks and changes the glasses design accordingly.

Requirements:
Python 3.x
OpenCV (cv2 module)
cvzone library (install using pip install cvzone)

Ensure you have the following cascade classifier XML files in your directory:

haarcascade_frontalface_default.xml
haarcascade_eye_tree_eyeglasses.xml
These files are typically available in your OpenCV installation or can be downloaded from OpenCV's GitHub repository

Run the script:python snaplens.py
Look at your webcam feed. It will detect your face and overlay different glasses designs from the Glasses folder (glass1.png to glass29.png) as you blink.

Configuration:
Adjust the path to the cascade classifier XML files (haarcascade_frontalface_default.xml and haarcascade_eye_tree_eyeglasses.xml) if they are stored in a different location.

Issues:
If you encounter any issues or have suggestions, please open an issue on GitHub.

Contact
Your Name:Manpreet Kaur
Your Email Address: Shineup2moon@gmail.com
