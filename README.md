Road Lane Detection using Computer Vision

This project demonstrates how to detect road lanes from driving video/images using computer vision techniques. The model processes frames to highlight lane markings and assist autonomous driving systems in understanding lane structure.

Project Overview

Goal: Detect and visualize lane lines on roads
Approach: Image processing using OpenCV and Python
Environment: Google Colab (Jupyter Notebook)
Techniques Used:
Grayscale Conversion
Gaussian Blur
Canny Edge Detection
Region of Interest Masking
Hough Line Transform

Files Included

`RoadLane_Detection.ipynb` — Main notebook with code and visual outputs

Requirements

To run this notebook, install the following Python libraries:

bash
opencv-python
matplotlib
numpy


How to Run

  Clone this repository or download the notebook.
  Open RoadLane_Detection.ipynb in Google Colab or Jupyter Notebook.
  Run each cell step by step.
  Upload a test video or image to see lane detection in action.

Future Improvements
  Integrate with real-time video streams
  Add deep learning (e.g., CNN) for better accuracy
  Support lane curvature prediction
