# Image-Video-Live-cam-Object-detection

# Object Detection with OpenCV, NumPy, and Matplotlib

This project demonstrates object detection using a pre-trained SSD MobileNet V3 model with OpenCV, NumPy, and Matplotlib. The project can perform object detection on images, video files, and live webcam feeds.

## Project Description

This repository contains code to:
- Detect objects in an image (`test_image.jpg`).
- Detect objects in a video file (`Video.mp4`).
- Detect objects from a live webcam feed.

The object detection model used is the SSD MobileNet V3 trained on the COCO dataset.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/object-detection-opencv.git
   cd object-detection-opencv
Install the required dependencies:
Make sure you have Python and pip installed. Then, install the required packages:

bash
Copy code
pip install opencv-python-headless numpy matplotlib
Download the model files:
Ensure you have the following files in your project directory:

ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt
frozen_inference_graph.pb
coco.txt (file containing COCO class names)
Place your test image and video in the project directory:

test_image.jpg (image for testing object detection)
Video.mp4 (video file for testing object detection)
