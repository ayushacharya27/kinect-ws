# Kinect ROS Workspace Setup

This guide walks you through setting up a ROS workspace for using the Kinect with the `freenect_stack` package. This package enables Kinect sensor integration with ROS.

## Prerequisites

Make sure the following are installed on your system:
- ROS (e.g., Noetic)
- Git

## Installation and Setup

Follow the steps below to set up the workspace and clone the necessary repository.

### 1. Create a ROS Workspace

First, create a workspace directory for your project:
```bash
mkdir -p ~/kinect_ws/src
cd ~/kinect_ws
```

### 2. Now make the source Directory

Now as you are in the Workspace create the source directory

```bash
mkdir src
cd src
git clone https://github.com/ros-drivers/freenect_stack.git
```

After this Do as Before , go to main workspace and catkin_make
