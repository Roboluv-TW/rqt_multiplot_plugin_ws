# rqt_multiplot_plugin_ws
Visualize MPU6050 IMU ROS topics

Original ROS package from  ETH zurich Autonomous Systems Lab(http://www.asl.ethz.ch/)

https://github.com/ethz-asl/rqt_multiplot_plugin

Visualize MPU6050 IMU sensor value from arduino mega

video:
https://www.youtube.com/watch?v=4hC1XsBPqeQ

environment:
ubuntu14.04 ROS indigo on Intel x86

####Tutorial:
https://hackmd.io/s/SJeUHP3bg

###Usage
Download arduino MPU6050.ino to your mega or uno 
by tutorial. https://hackmd.io/s/SJeUHP3bg


`git clone https://github.com/Roboluv-TW/rqt_multiplot_plugin_ws.git`
It is a ROS catkin_ws

`cd rqt_multiplot_plugin_ws`

`catkin_make`

`source environment.sh`

open 2 terminals 

####Terminal1  IMU send out topic (roscore and demo.launch)
`roslaunch mpu6050_serial_to_imu demo.launch`

####Terminal2  rqt_multiplot_plugin
`rosrun rqt_multiplot rqt_multiplot`

Have fun!
