# Face Detection and Recognition Project
# Overview
This project implements a face detection and recognition system using OpenCV and NumPy. It captures and processes face data to enable real-time facial recognition and generate voice responses. The system leverages the Haar Cascade classifier for face detection and the K-Nearest Neighbors (KNN) algorithm for face recognition.

# Features
+ Face Collection: Collects face data from a camera feed and stores it as NumPy arrays for training.

+ Face Recognition: Recognizes faces in real-time using KNN and matches them with the collected face data.

+ Voice Interaction: Provides a voice response using gTTS (Google Text-to-Speech) and pyttsx3 libraries to interact with recognized individuals.

+ Haar Cascade Classifier: Utilizes the Haar Cascade classifier to detect faces in the video feed.

# Requirements
+ Python 3.x
+ OpenCV
+ NumPy
+ gTTS
+ pyttsx3

# Usage
Collect Face Data:

Run the collect.py script to capture and save face data :
"python collect.py"

Recognize Faces:

Run the recognize.py script to start face recognition : 
"python recognize.py"

# Notes
+ Ensure that the camera is properly connected and functioning.
+ Place the haarcascade_frontalface_default.xml file in the project directory.
+ The voice responses are saved as MP3 files and can be played back when needed.
