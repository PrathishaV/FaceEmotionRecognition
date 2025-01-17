This project demonstrates real-time face emotion recognition using Python. 
The application leverages the facial_emotion_recognition library and OpenCV to detect and display emotions on live video captured from a webcam.

Features:
  Real-time emotion recognition.
  User-friendly interface using OpenCV.
  Lightweight and efficient for CPU-based execution.

Requirements:
To run this project, ensure you have the following installed:
  Python 3.6 or later
  OpenCV
  facial_emotion_recognition library

How It Works:
   The facial_emotion_recognition library processes each frame to detect faces and predict their emotions.
   OpenCV's imshow method displays the video feed with emotion labels superimposed on the detected faces.
   Pressing the "s" key exits the program and releases resources.

Customization:
   Modify the device parameter in EmotionRecognition to switch between CPU and GPU for processing.
   Adjust the webcam index in cv2.VideoCapture(0) if you have multiple cameras.

