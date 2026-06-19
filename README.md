# ROS 2 Jazzy Panda Robot Simulation

## Overview

This project demonstrates the installation and configuration of ROS 2 Jazzy and MoveIt 2 on Ubuntu 24.04 (WSL2). The project uses the Franka Emika Panda robot to explore robot visualization, motion planning, joint manipulation, and collision object management in RViz.

## Features

* ROS 2 Jazzy setup
* MoveIt 2 integration
* Panda Robot simulation
* Motion planning using MoveIt
* Joint state manipulation
* Collision object creation
* RViz visualization
* ROS 2 Control interface verification

## Technologies Used

* ROS 2 Jazzy
* MoveIt 2
* RViz2
* Ubuntu 24.04
* WSL2
* ROS2 Control

## Project Structure

```text
ROS2-Panda-Simulation/
├── screenshots/
├── report/
├── README.md
└── project_notes.md
```

## Installation

Update the system:

```bash
sudo apt update
sudo apt upgrade -y
```

Install ROS 2 Jazzy and source the environment:

```bash
source /opt/ros/jazzy/setup.bash
```

Install MoveIt:

```bash
sudo apt install ros-jazzy-moveit -y
```

## Running the Simulation

Launch the Panda robot demo:

```bash
ros2 launch moveit_resources_panda_moveit_config demo.launch.py
```

Launch RViz separately if needed:

```bash
rviz2
```

## Verification Commands

List ROS nodes:

```bash
ros2 node list
```

List topics:

```bash
ros2 topic list
```

Check controllers:

```bash
ros2 control list_controllers
```

Check hardware interfaces:

```bash
ros2 control list_hardware_interfaces
```

## Results

Successfully achieved:

* Panda robot visualization
* Motion planning
* Joint control
* Scene object creation
* Controller verification
* MoveIt integration

## Screenshots

Add screenshots of:

1. Panda robot in RViz
2. Motion Planning interface
3. Joint control panel
4. Collision object scene
5. Terminal outputs

## Learning Outcomes

This project helped in understanding:

* ROS 2 architecture
* Robot kinematics
* Motion planning
* MoveIt framework
* RViz visualization
* Robot controllers
* Simulation workflows

## Author

**Niharika C**

B.Tech Student | Robotics and ROS 2 Learner
