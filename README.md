# simple4wd
ROS packages to simulate a basic 4-wheel-drive robot in gazebo.


## Pacakges
Each package contains its own README for more information.
- simple4wd_description: the robot model in URDF, with gazebo configurations specific to the model
- simple4wd_gazebo: scripts to setup the simulation world and load in the the robot
- simple4wd_control: scripts to simulate controllers and communications to the robot in gazebo


## Usage
Display model in rviz.
```
roslaunch simple4wd_description simple4wd_rviz.launch
```

Run simulation in gazebo. This launch script also starts the ros_control script in the simple4wd_control package.
```
roslaunch simple4wd_gazebo simple4wd_gazebo.launch

```


## Example Robots to Reference
- https://github.com/ros-simulation/gazebo_ros_demos
- https://github.com/jackal/jackal
- https://github.com/husky/husky