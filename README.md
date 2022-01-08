# A Deep Learning Approach to Single-Image Depth Prediction

## Selected Results
![Results](large_out_prelim_labeled.png "Some Results")

## Overview
Depth information is essential to numerous computer vision tasks, from autonomous driving to augmented reality. Traditional methods of depth estimation, such as
LIDAR and RGBD cameras, can be expensive, large, and susceptible to adverse weather conditions. This project implements a deep-learning assisted, monocular approach to depth prediction,
which promises to alleviate some of the drawbacks of traditional methods.  

The network implemented in this project was first proposed by Eigen et al [1]. 

More detailed information can be found in the research paper MonocularDepthPred.pdf.

## Network
![network](Network.png "The Network")
The network proposed by Eigen et al [1].

## Training
The model is trained on the NYU Depth V1 labeled dataset [2]. We use 800 randomly selected image-depth pairs, partitioned into a training set of 640 pairs,
with the remainder serving as a validation set.

## Dataset
The NYU Depth V1 labeled dataset contains, among other variables, 2284 still images and their associated depths, which were recorded by the RGB and Depth cameras from a Microsoft Kinect [2].

## References
[1] https://arxiv.org/abs/1406.2283
[2] https://cs.nyu.edu/~silberman/datasets/nyu_depth_v1.html
