# unitree_g1_ros2_rviz

ROS 2 humble package for visualizing the Unitree G1 robot in RViz.

## Description
This package contains the URDF description and meshes for the Unitree G1 robot, along with launch files to visualize the model.

## Installation
1. Clone the repository into your ROS 2 workspace `src` directory.
2. Build the package:
   ```bash
   colcon build --packages-select unitree_g1_ros2_rviz
   ```
3. Source the workspace:
   ```bash
   source install/setup.bash
   ```

## Usage
To visualize the robot in RViz:
```bash
ros2 launch unitree_g1_ros2_rviz ros2_unitree_g1.launch.py
```

En una nueva terminal:
```bash
ros2 run joint_state_publisher_gui joint_state_publisher_gui 
```
