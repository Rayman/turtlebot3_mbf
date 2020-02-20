# Move base flex turtlebot3 demo

```sh
roslaunch turtlebot3_gazebo turtlebot3_world.launch
roslaunch mbf_turtlebot amcl_demo.launch
rosrun rviz rviz -d "$(rospack find turtlebot3_navigation)/rviz/turtlebot3_navigation.rviz"
```
