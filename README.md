# Gesture Recognition with Mediapipe

## Overview

This project utilizes the power of the Mediapipe library to perform real-time gesture recognition using a webcam. The code captures and processes keypoint data from different body parts, enabling the detection of various hand and body gestures.

## Features

- Real-time gesture detection using the webcam.
- Extraction of keypoint data for pose, face, and hand landmarks.
- Data collection for training a machine learning model to recognize specific actions.

## Getting Started

**Install dependencies**
   pip install tensorflow==2.4.1 tensorflow-gpu==2.4.1 opencv-python mediapipe sklearn matplotlib
**Data Collection**
The MP_Data folder structure is organized by actions, sequences, and frames.
Keypoint data is stored in numpy arrays for further processing.
**Model Training**
Train a machine learning model using the collected keypoint data.
Implement your own model or use existing frameworks to recognize gestures.
**Results**
Showcase the effectiveness of the gesture recognition system.
Share visualizations or performance metrics obtained during testing.
**Contributing**
Fork the repository and create a new branch.
Contribute improvements, bug fixes, or new features.
**Submit a pull request.**
