# COMMAND
## roslaunch scanner_lauch.launch use_new:=true
when using this command,the baselink and imu will be included to the list of links. Otherwise, the old model will be displayed in the rviz. The default value of the argment use_new is true
## roslaunch scanner_lauch.launch laser_include:=true
when using this command,the model include laser topics. Otherwise, only the robot model willb be displayed in the rviz. The default value of the argment laser_include is true
## roslaunch scanner_lauch.launch use_sim_time:=true
use_sim_time default is true

# ARGUMENT
## bag_file_name
rosbag's location

# NOTE 
Package navvis_description is required for this package. Both package should be placed under /src
