# ros2-tensorflow-object-detection
A ROS 2 package using TensorFlow with ROS2 for object detection. 

## System Requirements:
ROS 2 Humble
Python >=3.8
TensorFlow >=2.6
TensorFlow Object Detection API

## Installation
### Installation of Dependencies:
ROS 2 vision_msgs
ROS 2 image_tools
### Installation of the Package:
$ cd ~
$ mkdir ros2-tensorflow-obj-detection-ws
$ cd ros2-tensorflow-obj-detection-ws


## Build
$ cd ~/ros2-tensorflow-obj-detection-ws
$ colcon build

## Run
$ cd ~/ros2-tensorflow-obj-detection-ws
$ source ./install/local_setup.bash
$ ros2 run ros2-tensorflow-object-detection tf_detection_server
$ ros2 run ros2-tensorflow-object-detection tf_detection_client


## Notes
