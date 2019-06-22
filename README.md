# capra_arm

This repo contains the description for CAPRA's arm

## Dependecies
This package requires robotiq's robotiq_2f_140_gripper_visualization available at [https://github.com/ros-industrial/robotiq].

## To test with RViz
```
roslaunch capra_arm_description test_launch.launch
```
* Set Fixed Frame to root
* Add RobotModel view
* Play with joint_state_publisher sliders
