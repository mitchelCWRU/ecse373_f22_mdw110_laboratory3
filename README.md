Lab 3
==========

To launch RVIZ with the updated xacro file:

`roslaunch lab3 lab3.launch`

To lauch RVIZ with the previous version of the robot descritpion:

`roslaunch navvis_description display.launch use_xacro:=true use_joint_state_publisher_gui:=true`

lab3.launch usage:
------------------

Purpose: Launches the navvis robot description in RVIZ and visualized data from a specified bag file

lab3.launch arguments:
    - `bag_path`: Path to bag file
    - `bag_args`: Arugments for `rosbag` call such as `/tf_trajectory:=/tf --clock`
    - `map_config_path`: path to map .yaml config file
