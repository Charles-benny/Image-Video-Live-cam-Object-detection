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

lorry.jpg, lorry2.jpg (image for testing object detection)
people.mp4 (video file for testing object detection)
![Screenshot (229)](https://github.com/Charles-benny/Image-Video-Live-cam-Object-detection/assets/121818645/d8c71032-f063-4cae-856c-be7d80795a5e)


![Screenshot (231)](https://github.com/Charles-benny/Image-Video-Live-cam-Object-detection/assets/121818645/1636e12a-122e-483b-a743-f119cdba0020)


![Screenshot (233)](https://github.com/Charles-benny/Image-Video-Live-cam-Object-detection/assets/121818645/fae5ab30-8697-4e59-8987-e70b70c8ca71)
