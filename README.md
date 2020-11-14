# Ovis

This repo contains the files required to interact with Capra's Ovis 6DOF arm.

## Dependencies
- This package requires robotiq's `robotiq_2f_140_gripper_visualization` available at [ros-industrial/robotiq](https://github.com/ros-industrial/robotiq).
- [clubcapra/jog_control](https://github.com/clubcapra/jog_control)

### Launch the simulation
    
    roslaunch ovis_gazebo gazebo.launch
    roslaunch ovis_moveit_config ovis_gazebo_demo.launch 
    roslaunch ovis_jog_launch ovis.launch 
