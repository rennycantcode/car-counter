# Car Counter

## Overview

This Python script uses computer vision techniques to count vehicles in a given video. The implementation is based on the YOLO (You Only Look Once) object detection model, integrated with a SORT (Simple Online and Realtime Tracking) algorithm for tracking.

## Features

- **Object Detection:** Utilizes the YOLO model to detect vehicles in the video.

- **Tracking:** Implements the SORT algorithm for real-time tracking of detected vehicles.

- **Counting:** Tracks and counts vehicles crossing predefined lines in the video.

- **Visualization:** Displays the output with graphical overlays indicating the total count and count in specific directions.


## Prerequisites

Make sure you have the following dependencies installed:

- [Ultralytics YOLO](https://github.com/ultralytics/yolov5)

- OpenCV (`cv2`)

- cvzone

- SORT (Simple Online and Realtime Tracking)
