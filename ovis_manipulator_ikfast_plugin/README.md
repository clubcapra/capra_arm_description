# IKFast plugin

## How to generate the plugin
- Follow the documentation available at: https://ros-planning.github.io/moveit_tutorials/doc/ikfast/ikfast_tutorial.html
- Once the docker image is installed.
  - Add permissions to $USER:  https://stackoverflow.com/questions/48957195/how-to-fix-docker-got-permission-denied-issue
  - A reboot is required, a simple logout/login doesn't work.
- Run the ikfast_plugin_generator:
```
rosrun moveit_kinematics auto_create_ikfast_moveit_plugin.sh --iktype Transform6D $MYROBOT_NAME.urdf <planning_group_name> <base_link> <eef_link>
```
- Edit the kinematics.yaml file: https://ros-planning.github.io/moveit_tutorials/doc/ikfast/ikfast_tutorial.html#usage
