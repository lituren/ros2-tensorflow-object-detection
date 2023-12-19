# ros2-tensorflow-object-detection
A ROS 2 package using TensorFlow with ROS2 for object detection. 

## System Requirements:
ROS 2 Humble <br>
Python >=3.8 <br>
TensorFlow >=2.6 <br>
TensorFlow Object Detection API <br>

## Installation
### Installation of Dependencies:
$ sudo apt install ROS 2 vision_msgs <br>
$ sudo apt install ROS 2 image_tools <br>
### Installation of the Package:
$ cd ~ <br>
$ mkdir ros2-tensorflow-obj-detection-ws <br>
$ cd ros2-tensorflow-obj-detection-ws <br>


## Build
Navigate into the workspace directory <br>
$ cd ~/ros2-tensorflow-obj-detection-ws <br>
then <br>
$ colcon build <br>

## Run
Make sure to be in the workspace root, then <br>
$ source ./install/local_setup.bash <br>$ ros2 run ros2-tensorflow-object-detection tf_detection_server <br>
<br>
Open another terminal, source local_setup.bash, then: <br>
$ ros2 run ros2-tensorflow-object-detection tf_detection_client <br>


## Notes
