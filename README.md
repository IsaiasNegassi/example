# Vehicle Counting from Traffic Data Camera
## YOLOv7-DeepSORT Vehicle Detection and Tracking
This repository contains Python code for implementing YOLOv7 (You Only Look Once) object detection algorithms in PyTorch. The primary goal of this project is to detect and track vehicles in traffic surveillance video footage, utilizing the YOLO algorithm for detection and the DeepSORT (Deep Simple Online and Realtime Tracking) algorithm for tracking.

Features:
* Object Detection: The code includes a detector module capable of detecting various objects, including persons, horses, and sports balls. You can configure the detector to detect specific classes or all available classes.
* YOLOv7 Implementation: The repository provides scripts to load and utilize pre-trained YOLOv7 weights for object detection tasks.
* DeepSORT Integration: The implementation includes integration with the DeepSORT algorithm for object tracking. DeepSORT combines deep learning-based object detection with a sophisticated online tracking algorithm for robust and efficient tracking of objects over time.
* Counting and Analysis: Additionally, the code includes functionality for counting the number of vehicles that cross a specified line in the surveillance footage. It utilizes trajectory analysis to determine when vehicles cross the designated line and provides visualizations and data analysis for further insights.

## Instructions running the code
Install all the packages and import all the necessary listed libraries for a safe excussion
1. Install Numpy Version 1.22.0

