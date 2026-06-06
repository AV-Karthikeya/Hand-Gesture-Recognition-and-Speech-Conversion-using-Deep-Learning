# Hand Gesture to Speech Converter

## Overview

This project is a real-time Hand Gesture Recognition System that detects hand gestures using a webcam and converts recognized gestures into speech output. The system combines MediaPipe's hand-tracking capabilities with a Deep Learning-based Artificial Neural Network (ANN) model trained using TensorFlow/Keras.

The application captures hand landmarks from live video, predicts the performed gesture, displays the prediction on-screen, and generates corresponding audio using Google Text-to-Speech (gTTS).

---

## Technologies Used

* Python
* OpenCV
* MediaPipe
* TensorFlow / Keras
* NumPy
* gTTS

---

## Features

* Real-time hand tracking
* Gesture recognition using ANN
* Speech generation from detected gestures
* Live webcam feed with gesture display
* Easy-to-train custom gesture classes

---

## How It Works

1. Webcam captures live video.
2. MediaPipe detects hand landmarks.
3. Landmark coordinates are extracted.
4. TensorFlow ANN model classifies the gesture.
5. Predicted gesture is displayed on screen.
6. gTTS converts the gesture label into speech output.

---

## Requirements

Install the following dependencies:

### Python

* Python 3.x

### OpenCV

```bash
pip install opencv-python
```

### MediaPipe

```bash
pip install mediapipe
```

### TensorFlow

```bash
pip install tensorflow
```

### NumPy

```bash
pip install numpy
```

### Google Text-to-Speech

```bash
pip install gtts
```

---

## Running the Project

1. Clone the repository.
2. Install all required dependencies.
3. Open the project in PyCharm or VS Code.
4. Run:

```bash
python speechcode.py
```

5. Show a trained gesture in front of the webcam.
6. The system will predict the gesture and generate speech output.

Press **Q** to exit.

---

<img width="1918" height="1022" alt="dl" src="https://github.com/user-attachments/assets/79f95a11-916b-43e2-bc46-49913c4ab9ab" />

<img width="1543" height="538" alt="image" src="https://github.com/user-attachments/assets/2dad64bf-c2b7-4b9c-a5fc-2292a720e3fd" />

<img width="640" height="338" alt="image" src="https://github.com/user-attachments/assets/e3b9b44d-a111-47a5-821b-31de39116d6f" />


## Machine Learning / Deep Learning Used

### Hand Detection

* MediaPipe Hands

### Gesture Classification

* Artificial Neural Network (ANN)
* Built using TensorFlow/Keras

### Category

* Deep Learning
* Computer Vision
* Human-Computer Interaction

---

## Applications

* Sign Language Assistance
* Accessibility Solutions
* Human-Computer Interaction
* Gesture-Based Interfaces
* Smart Communication Systems

---

## Author

A V Karthikeya

B.Tech Computer Science Engineering

AI | Machine Learning | Deep Learning | Computer Vision
