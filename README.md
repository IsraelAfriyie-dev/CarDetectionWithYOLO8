### CarDetectionWithYOLO8
This repository contains a Python implementation for vehicle detection and lane analysis using the YOLOv8 (You Only Look Once) model. 
This repository contains a Python implementation for vehicle detection and lane analysis using the YOLOv8 (You Only Look Once) model. The project processes video footage to detect vehicles and identify lane markings, making it suitable for applications in traffic monitoring and automated driving systems.

#Features
Vehicle Detection: Utilizes YOLOv8 for real-time detection of vehicles in video frames, specifically targeting cars.
Lane Detection: Applies image processing techniques, including Gaussian blur and Hough Transform, to identify lane lines in the video.
Video Processing: Reads video files, applies detection algorithms frame by frame, and outputs a processed video with detected vehicles and lane lines highlighted.
Confidence Thresholding: Only displays detections with a confidence level above a specified threshold (0.5) for improved accuracy.
Output Video: Generates a new video file (processed_video.mp4) that contains the annotated frames.

#Prerequisites
Python 3.x
OpenCV
NumPy
YOLOv8 model weights (yolov8s.pt)
MoviePy
Google Colab (for uploading videos)

#How to Use
Upload a video file from your local machine.
Run the code to process the video.
Download the processed video with highlighted vehicles and lane markings.
