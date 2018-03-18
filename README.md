# Where Am I
Udacity Robotics Nanodegree project

## Requirements

1. Install necessary ROS packages.
```
apt-get update && apt-get install ros-kinetic-navigation ros-kinetic-map-server ros-kinetic-move-base
rospack profile
apt-get install ros-kinetic-amcl
```

## How To Use

1. Launch the gazebo world and the robot.
```
roslaunch udacity_bot udacity_world.launch
```

2. Launch the navigation stack.
```
roslaunch udacity_bot amcl.launch
```

3. Set the goal position.
```
rosrun udacity_bot navigation_goal
```
