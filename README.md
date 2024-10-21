# YOLO Object Detection

This project implements object detection using the YOLO (You Only Look Once) model from the Ultralytics library.

## Overview

This Jupyter notebook demonstrates how to:
- Install and import the YOLO model from Ultralytics
- Perform object detection on video input
- Display bounding boxes and class labels on detected objects

## Contents

- `yolo_object_detection.ipynb`: Main Jupyter notebook with the detection code
- `los_angeles.mp4`: Sample video file for detection 

## Requirements

- Python 3.x
- OpenCV (cv2)
- Ultralytics
- NumPy

## Installation

1. Clone this repository
2. Install the required libraries:
`pip install ultralytics opencv-python numpy`

Note: If you encounter issues installing Ultralytics, you may need to update your pip:
`pip install --upgrade pip`

## Usage

1. Ensure you have the video file `los_angeles.mp4` in the specified path
2. Open and run the Jupyter notebook

The notebook will:
- Initialize the YOLO model
- Process the video frame by frame
- Display detected objects with bounding boxes and labels

## Model

The project uses the YOLOv8n model from Ultralytics, which can detect 80 different object classes.

## Output

The script outputs a video stream with:
- Bounding boxes around detected objects
- Class labels for each detected object
- Confidence scores (printed to console)

## Customization

You can modify the script to:
- Use a different YOLO model variant
- Process images instead of video
- Adjust detection confidence thresholds
- Filter for specific object classes

## Troubleshooting

If you encounter a `ModuleNotFoundError` for Ultralytics, ensure that:
1. You've installed the library correctly
2. Your Jupyter kernel is using the correct Python environment

## Future Work

- Implement real-time webcam detection
- Add tracking functionality for moving objects
- Explore different YOLO model variants for speed/accuracy tradeoffs
