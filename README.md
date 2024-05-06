# People Fall Detection System

## Problem Statement

The project aims to develop a robust fall detection system using computer vision techniques. Falls among people, especially in areas like staircases, escalators, and steps, can be life-threatening. Hence, the solution must accurately identify falls while minimizing false positives.

## Technologies Used

- YOLO Computer Vision (CV) Library
- Pose Estimation algorithm
- Open-source models OWL-ViT and OWL-V2

## Input

Offline videos in mp4 format.

## Evaluation Criteria

1. High accuracy of fall predictions.
2. Minimization of false positives.

## Approach Document and Skeletal Solution

### Approach Document

The approach document outlines various potential strategies for fall detection and recommends the utilization of zero-shot object detection models during the training phase.

### Skeletal Solution

The skeletal solution provides a basic implementation of the training and prediction phases using the YOLO CV Library and Pose Estimation algorithm. It also integrates open-source models OWL-ViT and OWL-V2.

Both documents will be uploaded to GitHub by the end of May 6, 2024.

## Implementation

The provided Python code demonstrates the initial implementation of the fall detection system using YOLO CV Library and basic fall detection logic based on bounding box coordinates.

## Instructions

1. Install the required libraries: `cv2`, `cvzone`, `math`, `ultralytics`.
2. Download the YOLO model (`yolov8s.pt`) and the classes file (`classes.txt`).
3. Update file paths and parameters as needed in the Python script.
4. Run the Python script to start the fall detection system.

## Result
THIS CONTAINS 
![Demo Video](https://github.com/varshasenthil2003/Yavar/blob/main/result.mp4)

