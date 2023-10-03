## when using this command,the baselink and imu will be included to the list of links. Otherwise, the old model will be displayed in the rviz. The default value of the argment use_new is true
roslaunch scanner_lauch.launch use_new:=true
## when using this command,the model include laser topics. Otherwise, only the robot model willb be displayed in the rviz. The default value of the argment laser_include is true
roslaunch scanner_lauch.launch laser_include:=true
## use_sim_time default is true
roslaunch scanner_lauch.launch use_sim_time:=true
