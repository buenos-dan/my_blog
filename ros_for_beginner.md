# ROS for beginner
1. create a ros package
```
cd ~/catkin_ws/src
catkin_create_pkg <package_name> [depend1] [depend2] 
```
2. build package
```
cd ~/catkin_ws
catkin_make
```
3. add the workspace to your ROS environment
```
. ~/catkin_ws/devel/setup.bash
``` 

