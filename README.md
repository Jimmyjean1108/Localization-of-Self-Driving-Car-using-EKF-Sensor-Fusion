# Localization of Self-Driving-Car using EKF Sensor Fusion

### This is the public repo for project of Self-Driving Car at 2020 Fall
Self-Driving Car
National Chiao Tung University

### Main Objective
The goal of the project is to estimate the position of the self-driving car while driving. Two sensor sources are used in this project, which are GPS and radar odometry. EKF algorithm is used to estimate the position and covariance. 

### Performing Localization
A ROS envrionment with RViz installed is required for executing this program.
The performance of three different methods are compared, which are using GPS only, using radar odometry only, and fusing GPS and radar odometry.
# 
In the following figures, there would be 5 important information in each.
Blue arrows are the data from radar odometry, yellow circle is the data from GPS. Red arrows are the ground truth, the green points represent the results of EKF, and the purple ellipses mean the covariance.


The figure below shows the localization result of using GPS only.
![](https://i.imgur.com/k5bLRbS.jpg)

The figure below shows the localization result of using radar odometry only.
![](https://i.imgur.com/XEQ5SfR.jpg)

The figure below shows the localization result of sensor fusing the data from GPS and radar odometry.![](https://i.imgur.com/0y6w6BQ.jpg)

---

Dependencies:
* Ubuntu 18.04
* ROS melodic
* robot_localization <https://github.com/cra-ros-pkg/robot_localization>
* GeographicLab <https://github.com/Sciumo/GeographicLib>



---
Dataset:
nuScenes dataset <https://drive.google.com/file/d/1hTsymF4ErGuwd86Q8O58ArSq2aSYxSof/view>
