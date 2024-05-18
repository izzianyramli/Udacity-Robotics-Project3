# Udacity-Robotics-Project3
Udacity Robotics Software Engineer Nanodegree - Project 3: Where Am I?


## Build and Launch

1. Clone and initialize project with a catkin workspace
```
$ mkdir ~/catkin_ws && cd ~/catkin_ws
$ git clone https://github.com/izzianyramli/Udacity-Robotics-Project3.git
$ mv Udacity-Robotics-Project3 src
$ cd src && catkin_init_workspace
```

2. Go to `catkin_ws/` and build
```
$ cd ~/catkin_ws
$ catkin_make
```

3. Launch the robot world
```
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```

4. WIP
