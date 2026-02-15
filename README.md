# Basketball-3-point-shot-detection

## Overview
This system integrates YOLOv8 for object detection (player, ball and hoop) and MediaPipe Pose for extracting skeletal key points of the detected player. The objective is to build a complete pipeline capable of identifying shooting scenes and extracting biomechanical information from video frames.

## Models Used
- YOLOv8 (Object Detection)
- MediaPipe Pose (Skeleton Estimation)

## Dataset
Link provided in dataset_link.txt

## Results
Precision: 0.914
Recall: 0.862
mAP50: 0.929

## Future Improvements
- Larger dataset
- Better ball detection
- Temporal tracking
