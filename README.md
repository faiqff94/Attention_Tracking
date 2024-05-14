# Attention_Tracking
Attention tracking using OpenCV Python. The code will track the index finger and eye view of the user in webcam to declare if the two are aligned.

## A fully functional example project showing how to perform attention tracking in a video stream.

The project is an example built to demonstrate how to perform attention tracking of vision and finger point in python using OpenCV. Following are some applications of this example:
* Facial Expression recognition
* Eye Attention Tracking
* Finger point Tracking
* Blink Monitoring
* Mouth Tracking

## Detection Models
There are two different models used in this project:
* For face landmark detection
* For hand landmark detection
For face detection, I have used the "shape_predictor_68_face_landmarks" model from the dlib python library. The model detects 68 different landmarks on the face as shown in the image below.

![Face Landmarks](https://drive.google.com/file/d/1KFaZL5i6tw96BxxXMP2TYvDV87xcnzFG/view?usp=drive_link "Face Landmarks")

For hand detection I have used the built-in hand landmarks detection model in mediapipe python library. The model detects 20 different landmarks on the hands as shown in the image below.

![Hand Landmarks](https://drive.google.com/file/d/1Z-pCpIjjkOLnxStPn1UJooT9soxTSs6N/view?usp=drive_link "Hand Landmarks")

## How to run this example

* Install OpenCV, dlib, numpy and mediapipe libraries in python
* Download the model file provided with the code
* Run the example code
