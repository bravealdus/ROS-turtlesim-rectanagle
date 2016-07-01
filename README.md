# ROS-turtlesim-rectanagle

- install ROS (indigo used)
- sudo apt-get install ros-<rosdistro>-rosbridge-server (http://wiki.ros.org/rosbridge_suite)

[Inside ROS workspace]
- rosdep install turtle_actionlib
- rosmake turtle_actionlib
- rosrun turtle_actionlib shape_server
