# ROS-M2WR
First git clone this project to your catkin_ws
$cd catkin_ws
$catkin_make
$roscore
$roslaunch my_simulation my_world.launch
$source ~/catkin_ws/devel/setup.bash
$roslaunch m2wr_description spawn.launch
$roslaunch m2wr_description rviz.launch
Now setup fixed frame to /odom, add robot Model, add laser_scan , topic:m2wr_description
$source ~/catkin_ws/devel/setup.bash
rosrun motion_plan obstacle_avoidance.py
