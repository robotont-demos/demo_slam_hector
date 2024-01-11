# demo_slam_hector

This repository is a ROS package that contains 2D mapping demo showing the capabilities of the Robotont platform create a 2D map of the surrounding using Hector slam. 

To install Hector Slam, enter the following commands:<br/>
```bash
sudo apt update
sudo apt install ros-noetic-hector-slam
```

## Launching the demo

**On Robotont on-board computer**

Start the SLAM 2D:
```bash
roslaunch demo_slam_hector slam_2d.launch
```

### Note: 
It is necessary to have the base slam package, this can be found inside the [demo_slam](https://github.com/robotont-demos/demo_slam) repository.
