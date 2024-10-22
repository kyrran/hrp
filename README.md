# HTP Teleop Software

This software is designed to run under Linux with Ubuntu 16.04 and ROS Kinetic.

## Installation Instructions

Follow these steps to install the software on your host computer:

### 1. Unpack the Software
- Extract the `htp_teleop.zip` file into the `src` directory of your Catkin workspace.

### 2. Install Dependencies
Use the following commands to install the required dependencies:

```bash
sudo apt-get install ros-kinetic-gazebo-ros-control
sudo apt-get install ros-kinetic-joint-state-controller
sudo apt-get install ros-kinetic-hector-gazebo-plugins
sudo apt-get install ros-kinetic-hector-gazebo
sudo apt-get install python-pygame
sudo pip3 install -U scikit-fuzzy
