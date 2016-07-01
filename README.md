# ROS-turtlesim-rectanagle

- install ROS (indigo used)
- `sudo apt-get install ros-<rosdistro>-rosbridge-server` http://wiki.ros.org/rosbridge_suite
- create a workspace
- clone this repo in the `src/` folder inside the ROS workspace

 ### Inside ROS workspace
- `catkin_make`
- `rosdep install turtle_actionlib`
- `rosmake turtle_actionlib`
- `rosrun turtle_actionlib shape_server`
- `rosrun ivan_drawing rectangle_node`
