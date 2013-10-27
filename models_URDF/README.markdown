Basic URDF model of the collector bot.


```
rosrun xacro xacro.py collector_bot.xacro > collector_bot.urdf 
rosrun urdfdom check_urdf collector_bot.urdf

roslaunch urdf_tutorial display.launch model:=collector_bot.urdf
```