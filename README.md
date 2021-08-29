# Turtlebot3_Charging_Base
**This Repository will explain my 5th task: turtlebot3 charging base.
programs: Ubuntu 18.04 and ROS melodic.
## Steps:
1. in the terminal run this code:
* `export TURTLEBOT3_MODEL=burger`
* `roslaunch turtlebot3_gazebo turtlebot3_world.launch`

![terminal](https://github.com/faisalsaud63192/Turtlebot3_Charging_Base/blob/main/Images/terminal.png)

![gazebo](https://github.com/faisalsaud63192/Turtlebot3_Charging_Base/blob/main/Images/gazebo.png)

2. Open a new terminal and run navigation node:
* `export TURTLEBOT3_MODEL=burger`
* `roslaunch turtlebot3_navigation turtlebot3_navigation.launch `

![rviz](https://github.com/faisalsaud63192/Turtlebot3_Charging_Base/blob/main/Images/rviz.png)

3. To control, open a new terminal and run this code:
* `export TURTLEBOT3_MODEL=burger`
* `roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch`

![control](https://github.com/faisalsaud63192/Turtlebot3_Charging_Base/blob/main/Images/control.png)

simulation video in the videos file.

Task is done.
