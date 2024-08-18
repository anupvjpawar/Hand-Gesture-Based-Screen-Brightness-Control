# **Real-Time Hand Gesture-Based Screen Brightness Control**

This project demonstrates a **real-time hand gesture-based screen brightness control system** using **OpenCV**, **MediaPipe**, and **Screen Brightness Control (SBC)**. The system captures video from a webcam, detects hand landmarks, and adjusts the screen brightness based on the distance between the thumb and index finger.

## **Features**

- **Real-Time Hand Detection:** Detects hand landmarks in real-time using a webcam feed.
- **Gesture Recognition:** Measures the distance between the thumb and index finger to determine the brightness level.
- **Screen Brightness Control:** Dynamically adjusts the screen brightness based on hand gestures.
- **Visual Feedback:** Displays hand landmarks and the line connecting the thumb and index finger on the video feed.

## How It Works
Video Capture: Captures video from the default webcam.
Hand Landmark Detection: Uses MediaPipe to detect hand landmarks in the video stream.
Gesture Recognition: Calculates the distance between the thumb and index finger.
Brightness Adjustment: Maps the calculated distance to a brightness level between 0 and 100, then adjusts the screen brightness accordingly.
Display Results: The video feed shows hand landmarks, the line connecting the thumb and index finger, and the calculated brightness level in real-time.
File Descriptions
hand_gesture_brightness_control.py: The main Python script that runs the real-time hand gesture detection and screen brightness control using OpenCV, MediaPipe, and SBC.

## **Requirements**

- **Python 3.x**
- **OpenCV** (`opencv-python` package)
- **MediaPipe** (`mediapipe` package)
- **Screen Brightness Control** (`screen-brightness-control` package)
- **Numpy** (`numpy` package)

## Usage
Run the Hand Gesture-Based Brightness Control System:
Execute the Python script to start the real-time hand gesture detection and screen brightness control:

## **Installation**

To set up this project, follow these steps:

### **Install Required Python Packages:**

Install the necessary Python packages using pip:

```bash
pip install opencv-python mediapipe screen-brightness-control numpy
'''
