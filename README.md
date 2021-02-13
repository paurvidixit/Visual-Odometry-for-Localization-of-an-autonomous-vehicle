# Visual-Odometry-for-Localization-of-an-autonomous-vehicle

C++, openCV implementation of Visual Odometry pipeline for KITTY dataset (self-driving car)

## Algorithm

ORB feature detector and descriptor to find define keypoints in grayscale images.

KLT tracker to track corresponding points in consecutive images.

Nister's 5 point algorithm is used to estimate the essential matrix.

Since it is monocular VO, it doesnot provide any information about scale. Scale can be computed from some external means/ sensors. 

For visualization purpose, I am computed the scale from the ground truth.

## Results

