# UR5_VentionRail
UR5 with Vention Rail Description and Moveit Config

Package overview
----------------

* `ur5e_linear`: URDF description of the robot
* `ur5e_linear_moveit_config`: MoveIt! launch and configuration files



Installation
------------

First, [install ROS](http://wiki.ros.org/ROS/Installation). Then:

```bash
# create a catkin workspace and clone all required ROS packages
mkdir -p ~/linear_ws/src
cd ~/linear_ws/src/
git clone https://github.com/TomGrimwood/UR5_VentionRail.git

UR5_VentionRail/install-deps.sh
UR5_VentionRail/build.sh
```


Quick start
-----------

The following examples describe how to use the robot in simulation.

```bash
# source the workspace you just built
source ~/linear_ws/devel/setup.bash
# run MoveIt! Demo
roslaunch ur5e_linear_moveit_config demo.launch
```

