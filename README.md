
```markdown
# Scara Robot Simulation and Control using ROS and MATLAB

## Overview
This project simulates and controls a SCARA (Selective Compliance Assembly Robot Arm) robot using ROS (Robot Operating System) and MATLAB. It includes configuration files, launch files, 3D models, and control scripts for an integrated simulation environment.

## Repository Structure
- config/: ROS configuration files.
- launch/: Launch files for ROS nodes.
- meshes/: 3D models for the SCARA robot.
- urdf/: URDF files for robot description.
- CMakeLists.txt: CMake build configuration.
- README.md: Project documentation.
- export.log: Export log file.
- package.xml: Package configuration.

## Requirements
- ROS: Install ROS on your system.
- MATLAB: Install MATLAB with the required toolboxes.

## Installation
1. Clone the Repository
    ```sh
    git clone https://github.com/bethlehem-dagnachew/scara-robot-simulation-and-control-using-ros.git
    cd scara-robot-simulation-and-control-using-ros
    ```

2. Build the ROS Package
    ```sh
    cd catkin_ws
    catkin_make
    source devel/setup.bash
    ```

3. Launch the ROS Nodes
    ```sh
    roslaunch scara_robot scara_simulation.launch
    ```

## Simulation and Control
1. Launch the Simulation
    ```sh
    roslaunch scara_robot scara_simulation.launch
    ```

## Usage
- Simulation: Use URDF files and launch configurations to simulate the SCARA robot.
- Control: Use MATLAB scripts to send control commands.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for discussion.


```
