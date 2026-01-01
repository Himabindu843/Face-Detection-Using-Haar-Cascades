

# Real-Time Multi-Face and Eye Detection using OpenCV

## Project Overview

This project implements a **real-time multi-face and eye detection system** using **Haar Cascade Classifiers** provided by OpenCV.
The system detects **multiple human faces**, identifies **eyes within each face**, and displays **performance metrics such as FPS (Frames Per Second)**.

The project is designed to understand **classical computer vision techniques**, real-time image processing, and the limitations of traditional object detection methods.

## Objectives

* Detect multiple human faces from images and video streams
* Perform eye detection within detected face regions
* Measure real-time performance using FPS
* Analyze strengths and limitations of Haar Cascade–based detection


## Technologies Used

* **Programming Language:** Python
* **Library:** OpenCV
* **Environment:** Google Colab (image-based testing), Local Machine (webcam testing)
* **Concepts:** Computer Vision, Object Detection, Real-Time Processing


## Implementation Details

### 1. Haar Cascade Classifier

Haar Cascades are machine learning–based classifiers trained using:

* Haar-like features
* Integral images
* AdaBoost algorithm

They are lightweight and suitable for **real-time applications**.

### 2. Detection Pipeline

1. Input image / video frame is captured
2. Image is converted to grayscale
3. Face detection is applied using Haar Cascade
4. Eye detection is performed within face regions
5. Bounding boxes are drawn
6. FPS and face count are displayed

## Features

✔ Multi-face detection
✔ Eye detection within face region
✔ Face count display
✔ FPS (performance analysis)
✔ Works on images and webcam feed
## How to Run (Google Colab – Image Mode)

pip install opencv-python

1. Upload an image containing faces
2. Load Haar Cascade XML files
3. Run the detection script
4. View output with bounding boxes and metrics
## How to Run (Local System – Webcam Mode)

python face_eye_detection.py

* Press **`q`** to exit webcam window
* Webcam testing is done locally since Google Colab does not support direct webcam access

## Performance Metrics

* **FPS (Frames Per Second)** is calculated to measure real-time efficiency
* Detection accuracy varies with:

  * Lighting conditions
  * Face orientation
  * Distance from camera

## Limitations

* Sensitive to lighting variations
* Reduced accuracy for side-face poses
* Not as robust as deep learning–based detectors

## Future Enhancements

* Replace Haar Cascade with CNN or DNN-based face detectors
* Improve robustness under low-light conditions
* Add face recognition functionality
* Deploy as a real-time monitoring application

## Learning Outcomes

* Understanding classical object detection techniques
* Real-time image processing using OpenCV
* Performance evaluation using FPS
* Practical exposure to computer vision workflows
