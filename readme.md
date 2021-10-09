# UR robot arm with Robotiq gripper grasp simulation in Gazebo

## Platform

``ubuntu20.04`` `` ros-noetic``  ``gazebo9``

## Install

``catkin_make``

``source devel/setup.zsh``

Some dependencies such as Moveit should be installed for compilation. Do it according to your compilation debug instructions.

## Demo

``roslaunch smart_grasping_sandbox_sample main.launch ``

``roslaunch urwh_moveit_config urwh_planning_example_execution.launch``

``rosrun smart_grasping_sandbox_sample grasping_demo.py``

then you will get the result like below:

## About Robotiq gazebo plugin

| Plugin                               | Link                                                                  | Result                                 |
| ------------------------------------ | --------------------------------------------------------------------- | -------------------------------------- |
| roboticsgroup_gazebo_plugins         | https://github.com/roboticsgroup/roboticsgroup_gazebo_plugins         | deprecated, so I didn''t test          |
| roboticsgroup_upatras_gazebo_plugins | https://github.com/roboticsgroup/roboticsgroup_upatras_gazebo_plugins | It does not work. The finger will spin |
| plugin in this repo                  |                                                                       | works!                                 |
