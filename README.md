# SLAM-Simulation-ROS-Gazebo
Demo that performs Simultaneous Localization And Mapping (SLAM) using ready made Robot Operating System(ROS) packages and Gazebo Simulator.

### Dependencies
| ROS Melodic | Gazebo | Catkin | Rviz |
| ------ | ------ | ------ | ------ |

### How to Build
Run the following command in the current directory:
```sh
catkin_make
```

### How to Run The world on Gazebo
Run the following command in the current directory:
```sh
source devel/setup.bash
roslaunch turtlebot3_gazebo turtlebot3_world.launch
```

### How to Move the Robot using Keyboard
Run the following command in the current directory:
```sh
source devel/setup.bash
roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```

### How to visualize the map on RViz using hector SLAM algorithm
Run the following command in the current directory:
```sh
source devel/setup.bash
roslaunch turtlebot3_slam turtlebot3_slam.launch
```
then move the robot to build the map.
