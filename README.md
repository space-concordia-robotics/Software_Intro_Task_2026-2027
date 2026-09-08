# Repository Description
Intro task repository to be forked by new potential software members who are interested in contributing to the software of the Robotics division of Space Concordia. 
The instructions of the software introduction task can be found in this README.md below.
This repository contains a ROS2 workspace where packages can be added inside of the /src folder.
Keep in mind that the URDF is very detailed and might need to be modified in order to reduce detail.

# 1. Creating a local repository
1.1. Make sure that your GitHub account is connected to your computer.
1.2. Fork this repository. This is where you are going to write your implementation of the intro task.

# 2. Fix the intro_rover_description ROS2 package
2.1. Apply the changes necessary to the files of the package in order to get it to work properly.

# 3. Visualise the robot in RViz
3.1. Create a launch file to visualise the rover in the RViz software.

# 4. Create a Ros2 infrastructure to control the rover in RViz
4.1. Create a node to manually control each joint of the rover.
4.2. Create a node to make the rover dance. This should be a reprogrammed sequence or a function of the joint states over time. 

# 5. Simulate the robot in Gazebo Harmonic
5.1. Create a launch file that spawns the rover in a Gazebo world. Please make sure to use Gazebo Harmonic as this version of Gazebo works better with ROS2 Jazzy.
5.2. Control the rover with the control infrastructure built in part 4. and 

# Be ready to present your solution
