## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
The name of this project is 'Go Chase It!".  This is the 2nd project for the Udacity Robotics Software Engineering program.  The purpose of this project is to practice the control of robot and the processing of sensor data.
	
## Technologies
Project is requires:
* Udacity Workspace or a Virtual Environment with image provided by Udacity
* Robot Operating System, “ROS"
* Gazebo
* RViz

The robot uses:
* A plugin for the camera sensor, libgazebo_ros_camera.so.
* A plugin for the Hokuyo lidar sensor, libgazebo_ros_laser.so.
* A plugin for the wheel joints actuator, libgazebo_ros_skid_steer_drive.so.
	
## Setup
To run this project, log into the the Udacity Workspace:

1. Open a console, download and build the project
```
$ cd <to the catkin workspace 'src' subfolder>
$ git clone https://github.com/peggycyggep/Project2
$ cd ..
$ catkin_make
```
2. In the same console or open another console, launch the robot
```
$ cd <to the catkin workspace>
$ source devel/setup
$ roslaunch my_robot world.launch
```
3. Open another console and launch the ball chaser
```
$ cd <to the catkin workspace>
$ source devel/setup
$ roslaunch ball_chaser ball_chaser.launch
```
