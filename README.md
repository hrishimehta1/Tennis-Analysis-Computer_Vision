
# Tennis Analysis

## Introduction
This project is designed to analyze tennis players in video footage, measuring their speed, the speed of their shots, and the number of shots. By leveraging YOLO for player and tennis ball detection, and using Convolutional Neural Networks (CNNs) to extract court keypoints, this hands-on project is ideal for honing your machine learning and computer vision skills.


## Output Videos
Here is a screenshot from one of the output videos:

![Screenshot](screenshot.jpeg)

## Models Used
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
