# ROS2-DIFF-DRIVE-ROBOT

you need to have installed:
->ros-xacro: (sudo apt install ros-<ros2-distro>-xacro)
->ros-joint-state-publisher: (sudo apt install ros-<ros2-distro>-joint-state-publisher-gui)
->gazebo-ros: (sudo apt install ros-<ros2-distro>-gazebo-ros-pkgs)

To view the urdf in rviz open 3 terminals:
-> 1st-ros2 launch my_bot rsp.launch.py
-> 2nd- rviz2
-> 3rd ros2 run joint_state_publisher_gui joint_state_publisher_gui 

To view and control the robot in gazebo open 2 terminals:
-> 1st- ros2 launch my_bot launch_sim.launch.py
-> 2nd- ros2 run teleop_twist_keyboard teleop_twist_keyboard

https://github.com/odobot/ROS2-DIFF-DRIVE-ROBOT/assets/103571670/23f5d763-e2cb-4b88-85ef-72480273b8d6

