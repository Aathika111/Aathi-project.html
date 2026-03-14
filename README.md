# Hand-Tracking Volume Controller

A real-time Python application that uses Computer Vision to control system volume via hand gestures.

## Why this project?
I built this to explore the intersection of **Artificial Intelligence** and **Human-Computer Interaction (HCI)**. It solves the need for touchless control using a standard webcam.

## Tech Stack
* **Language:** Python
* **Computer Vision:** OpenCV
* **AI Framework:** MediaPipe (for hand landmark detection)
* **Audio Control:** Pycaw

## Key Features
* **Landmark Tracking:** Detects 21 hand points in real-time.
* **Gesture Mapping:** Measures the distance between the thumb and index finger to adjust volume.
* **Visual Feedback:** Shows real-time volume bars and percentages on the camera feed.

## Installation
1. Clone this repository.
2. Install requirements:
   ```bash
   pip install opencv-python mediapipe pycaw
