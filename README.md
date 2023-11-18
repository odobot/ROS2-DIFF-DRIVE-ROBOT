# ROS2-DIFF-DRIVE-ROBOT
## Installation
The package was made using [ROS2 Humble](https://docs.ros.org/en/humble/index.html)
## Dependencies
You need to have installed:
<br>
1. ros-xacro:
   ```console
   sudo apt install ros-<ros2-distro>-xacro
   ```
2. ros-joint-state-publisher:
   ```console
   sudo apt install ros-<ros2-distro>-joint-state-publisher-gui
   ```
3. gazebo-ros:
   ```console
   sudo apt install ros-<ros2-distro>-gazebo-ros-pkgs
   ```
## :movie_camera: Rviz
To view the urdf in rviz open 3 terminals:
<br>
On the first terminal (needs to the terminal you sourced your setup.bash file in) type: 
```console
  ros2 launch my_bot rsp.launch.py
  ```
Second terminal
 ```console
  rviz2
  ```
third terminal
 ```console
  ros2 run joint_state_publisher_gui joint_state_publisher_gui
 ```
## 🎥 Gazebo
### Default world
To view and control the robot in gazebo:
<br>
Run:
```console
ros2 launch my_bot launch_sim.launch.py
```
```console
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```
https://github.com/odobot/ROS2-DIFF-DRIVE-ROBOT/assets/103571670/23f5d763-e2cb-4b88-85ef-72480273b8d6

