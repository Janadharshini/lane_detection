# LANE DETECTION


Overview:
This project aims to detect and visualize lanes on the road using computer vision techniques. Lane detection is a critical component of autonomous vehicles and advanced driver assistance systems (ADAS).

Table of Contents:
Introduction Dependencies Algorithm Explanation Results

Introduction:
Lane detection is an essential task in the field of autonomous driving and computer vision. This project demonstrates a simple lane detection algorithm using Python and OpenCV. It processes images or videos of the road and highlights the detected lanes.

Dependencies:
To run this project, you will need the following dependencies: Python (>=3.6) OpenCV (>=4.0) NumPy (>=1.16) You can install these dependencies using pip: pip install opencv-python numpy

Algorithm Explanation:
Our lane detection algorithm follows these steps;

Image Preprocessing:
Convert the input frame to grayscale and apply Gaussian blur to reduce noise.

Edge Detection:
Use Canny edge detection to detect edges in the image.

Region of Interest (ROI) Selection:
Define a region of interest to focus on the road area and mask out the rest.

Hough Transform:
Apply Hough line transform to detect lines in the ROI.

Line Filtering and Averaging:
Filter and average the detected lines to obtain two primary lane lines.

Lane Visualization:
Draw the detected lane lines on the original frame.

Results: You can find sample images and videos in the samples directory to see the lane detection algorithm in action. Feel free to experiment with different input data and parameters to achieve
