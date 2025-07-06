## ROS2 Robotics Project

This repository contains a complete robotics project developed using **ROS2 (Robot Operating System 2)**. The project focuses on manual teleoperation of a robot model, allowing a human operator to control the robot's movement and actions within a ROS2 workspace.

## 📁 Project Structure

* `src/` - Contains custom ROS2 packages including:

  * `my_robot_description/` — URDF files and robot model definitions
  * `my_robot_bringup/` — Launch files and configuration for starting the robot
  * `my_robot_control/` — Custom ROS2 nodes for robot control logic
* `launch/` - Launch files for bringing up the system
* `CMakeLists.txt` - Build configuration
* `package.xml` - ROS2 package metadata

## 🚀 Features

* ROS2 nodes for manual robot control and simulation
* Structured launch system for easy startup
* Modular and scalable package design
* Tested with ROS2 Humble

## 💡 Usage

1. Clone this repository:

```bash
git clone https://github.com/Zendron12/ros2_robotics_project-.git
```

2. Build the workspace:

```bash
colcon build
```

3. Source the setup file:

```bash
source install/setup.bash
```

4. Launch the system:

```bash
ros2 launch my_robot_bringup bringup.launch.py
```

## 🖼️ Simulation Screenshots

![Simulation 1](https://github.com/Zendron12/ros2_robotics_project-/blob/main/images/image.png?raw=true)

![Simulation 2](https://github.com/Zendron12/ros2_robotics_project-/blob/main/images/image2.png?raw=true)

![Simulation 3](https://github.com/Zendron12/ros2_robotics_project-/blob/main/images/image3.png?raw=true)

## 📌 Requirements

* ROS2 (Humble or later)
* Colcon
* Python 3.x

## 📄 License

This project is licensed under the MIT License — see the LICENSE file for details.

## ✍️ Author

Hesham — Student at The Hashemite University, passionate about Big Data, AI, and Robotics.
