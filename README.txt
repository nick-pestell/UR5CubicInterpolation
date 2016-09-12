Python code for moving UR5 end effector in a straight line trajectory with a cubic displacment time parametization in ROS.

ros version: indigo 

ur_modern_driver: https://github.com/ThomasTimm/ur_modern_driver

The program uses the MoveIt! API with waypoints. 

****************

input arguments: target end effector position and orientation followed by desired average velocity; (x y z roll pitch yaw Vavg)

