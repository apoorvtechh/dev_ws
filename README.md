**ROS2 Navigation and SLAM Implementation on Raspberry Pi 3 with LiDAR Sensor**
Overview

This repository contains code for implementing navigation (Nav2) and SLAM (Simultaneous Localization and Mapping) using ROS2 on a Raspberry Pi 3 along with a LiDAR sensor. The project aims to enable autonomous navigation and mapping capabilities for small robotic platforms.
**Requirements**

    Raspberry Pi 3 (or higher)
    LiDAR sensor (e.g., RPLIDAR)
    ROS2 Foxy Fitzroy or later
    Navigation2 (Nav2) package
    SLAM Toolbox

**Installation**

    Clone this repository into your ROS2 workspace.
    Install ROS2 and required packages.
    Configure your LiDAR sensor and ensure it publishes sensor data.
    

**Usage**

    Launch the ROS2 navigation stack: ros2 launch nav2_bringup tb3_simulation_launch.py
    Launch SLAM mapping: ros2 launch slam_toolbox online_async_launch.py
    Visualize mapping results: ros2 run rviz2 rviz2 -d <path_to_rviz_config_file>
    

**Troubleshooting**

    If you encounter issues with LiDAR sensor data, check connections and ensure proper configuration.
    Refer to ROS2 and package documentation for troubleshooting specific errors.

**Contributing**

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.
License


**Credits**

This project was inspired by Articulated Robotics

**Contact**

For any inquiries or support, contact apoorvtechh@gmail.com.
