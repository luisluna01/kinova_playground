# kinova_playground
A personal project to learn sim skills through a kinova arm in MuJoco

## Requirements
- `C++17`
- `ROS Humble`

## Dependencies
- [MuJoCo ros2_control](https://github.com/ros-controls/mujoco_ros2_control) [branch: `main`]

## Quick Start
Import all necessary dependencies:
```bash
cd <path to workspace>/src/kinova_playground # Navigate to repo
vcs import --recursive < vcs_workspace.repos
```

Build the workspace

```bash
cd ../../ # Navigate to workspace
colcon build --symlink-install --cmake-args -DCMAKE_BUILD_TYPE=Release
```
