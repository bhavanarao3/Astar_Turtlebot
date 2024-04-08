# TurtleBot Path Planning and Control

## Overview
This Python script demonstrates path planning and control for a TurtleBot robot navigating in an environment with obstacles. It utilizes the A* algorithm for path planning and a simple proportional-derivative (PD) controller for robot motion control.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- OpenCV (cv2)
- Math
- Time
- heapq
- csv
- rclpy (ROS 2 Python client library)
- geometry_msgs.msg.Twist (ROS 2 message type for controlling robot velocity)

## Usage
1. Make sure all the required libraries are installed.
2. Run the Python script using the command `python3 path_planning_and_control.py`.
3. Follow the instructions to input the start and end points for path planning.
4. The script will visualize the environment, plan the path using A* algorithm, and control the TurtleBot to follow the planned path.

