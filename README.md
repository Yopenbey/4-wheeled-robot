# 4-wheeled-robot

1. Create your workspace: mkdir ~/home/workspace/catkin_ws/src

2. Go to catkin_ws (cd ..) and build it: catkin_make

3. clone the repository inside the src package: git clone https://github.com/Yopenbey/4-wheeled-robot.git

4. Go back to catkin_ws and after build it again, source it: source devel/setup.bash

5. Launch the robot: roslaunch my_robot world.launch

6. Launch the ball chaser: roslaunch ball_chaser ball_chaser.launch

7.Otherwise, you can look for the teleop commands in this site (to control the robot manually): http://wiki.ros.org/stdr_simulator/Tutorials/Teleop%20with%20teleop_twist_keyboard

