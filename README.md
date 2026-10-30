# TurtleBot3 Autonomous Navigation using ROS 2 and Nav2

## Project Overview

This project demonstrates autonomous navigation of a TurtleBot3 robot in a Gazebo simulation environment using ROS 2 Jazzy and Navigation2 (Nav2).

## Technologies Used

* Ubuntu 24.04
* ROS 2 Jazzy
* Gazebo
* TurtleBot3 Waffle
* Navigation2
* RViz

## Project Objectives

* Simulate TurtleBot3 in Gazebo.
* Visualize the robot and environment in RViz.
* Set the robot's initial position.
* Send navigation goals.
* Demonstrate autonomous navigation and obstacle avoidance.

## Installation

Install ROS 2 Jazzy and the required Nav2 packages.

```bash
sudo apt update
sudo apt install ros-jazzy-navigation2 ros-jazzy-nav2-bringup -y
sudo apt install 'ros-jazzy-nav2-minimal-tb*' -y
```

## Run Simulation

```bash
source /opt/ros/jazzy/setup.bash
ros2 launch nav2_bringup tb3_simulation_launch.py headless:=False
```

## Robot Operation

1. Open RViz.
2. Set the initial robot position using 2D Pose Estimate.
3. Select Nav2 Goal.
4. Choose a destination.
5. Observe autonomous navigation in Gazebo.

## Results

Screenshots and demonstration videos will be added after successful testing.

## Author

Srinivas Pulikonda
