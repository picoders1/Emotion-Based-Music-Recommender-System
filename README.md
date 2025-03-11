# Facial emotion detection based music recommendation system

### About
This repository demonstrates an end-to-end pipeline for real-time Facial emotion recognition application along with reccommending music based on detected emotions.
Done in three steps:
1. Face Detection: from the video source using OpenCV.
2. Emotion Recognition: using a model trained by using Mediapipe library.
3. Music Recommendation: Using detected emotion to create a search query on Youtube

The model is trained for 50 epochs and runs at 87% accuracy.
![image](https://user-images.githubusercontent.com/81975567/170823927-bd313103-7b34-42fd-9635-1b913ec65667.png)

### Dependencies
This project depends on Python and following packages which can be easily installed through `requirements.txt` file by running the following command:
`pip install -r requirements.txt`
- Python 3.9
- pip 22.1.1
- streamlit 1.9.1
- streamlit-webrtc 0.37.0
- opencv-python 4.5.5.64
- mediapipe 0.8.10
- face-Recognition
- deepface

### System Architechture
![image](https://user-images.githubusercontent.com/81975567/170823667-70ffb002-f1bd-4578-b9a0-4ed32baee51d.png)

### Repository Structure
 This repository is organised as:
 - [app](/app.py) This file contain the setup of final web app.
 - [model](/model.h5) This file contains the trained model.
 - [Emotion Detection](./Emotion%20Detection) This folder contains python scripts to train the model.

### Future Scope
- Deploying the web app.
- Integration of an inbuilt music player using  SpotiPy library, with spotify authentication.
- Addition of more gestures, and control of volume using gesture detection.
- Improved Reliablity and addition of User Feedback


## Thank You!!

