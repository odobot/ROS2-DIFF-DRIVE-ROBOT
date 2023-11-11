# ROS2-DIFF-DRIVE-ROBOT

You need to have installed:
<br>
1. ros-xacro: `sudo apt install ros-<ros2-distro>-xacro`
1. ros-joint-state-publisher: `sudo apt install ros-<ros2-distro>-joint-state-publisher-gui`
1. gazebo-ros: `sudo apt install ros-<ros2-distro>-gazebo-ros-pkgs`

To view the urdf in rviz open 3 terminals:
* `ros2 launch my_bot rsp.launch.py`
* `rviz2`
* `ros2 run joint_state_publisher_gui joint_state_publisher_gui`

To view the robot in gazebo terminal, run:
* `ros2 launch my_bot launch_sim.launch.py`
* `ros2 run teleop_twist_keyboard teleop_twist_keyboard`

https://github.com/odobot/ROS2-DIFF-DRIVE-ROBOT/assets/103571670/23f5d763-e2cb-4b88-85ef-72480273b8d6

