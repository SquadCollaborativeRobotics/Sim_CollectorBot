CollectorBotSim - Collector Robot Simulation Prototype
===============

Basic SDF Gazebo model of the collector bot, as well as a URDF model for rviz.

Populated Gazebo with a willow garage office environment, some random furniture, 2 collector robots (blue) and one Pioneer P2DX robot (black), to be replaced with a P3DX.
![Gazebo sim](http://i.imgur.com/IwvOHYK.png)

Banging into door
![door-hit](http://i.imgur.com/Pe8OOFx.png)

Flipped upside down
![flipped](http://i.imgur.com/8DkWURQ.png)

Rviz model
![Rviz model](http://i.imgur.com/5eSlItk.png)

```
rosrun xacro xacro.py collector_bot.xacro > collector_bot.urdf 
rosrun urdfdom check_urdf collector_bot.urdf

roslaunch urdf_tutorial display.launch model:=collector_bot.urdf
```