husky_customization
===================

Templates for user customization of Husky description (URDF) and Gazebo configuration.

 - husky_custom_description : Template for creating a custom URDF description Husky robot
 - husky_custom_gazebo : Template for creating a custom Gazebo simulation configuration

For Husky instructions and tutorials, please see http://wiki.ros.org/Robots/Husky

For this installation, local (user laptop for example) pre-requisites can be installed with:
```
rosdep install robotiq_modbus_tcp
sudo apt-get install ros-indigo-soem -y
sudo apt-get install ros-indigo-ur-modern-driver -y
sudo apt-get install ros-indigo-moveit-planners* -y
sudo apt-get install ros-indigo-moveit-ros-planning* -y
sudo apt-get install ros-indigo-moveit-ros-move-group -y
```
To launch the planner on a local laptop, ensure ROS_IP (your machine IP) and the computer's IP (Husky IP) are exported properly:
```
export ROS_IP=192.168.131.X
export ROS_MASTER_URI=http://cpr-kaust02:11311
```
