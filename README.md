# capra_arm_description

This repo contains the description for CAPRA's arm

## Dependecies
This package requires robotiq's robotiq_2f_140_gripper_visualization available at [https://github.com/ros-industrial/robotiq].

## To test with RViz
```
roslaunch capra_arm_description test_launch.launch sim:=true
```
Set Fixed Frame to base_link
Then add a RobotModel view.
