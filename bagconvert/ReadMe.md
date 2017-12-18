# bagconvert

* Takes a bag file and converts it to a matlab file
* Needs to be inside of your ros workspace
* Matlab should be installed on your system

# Installation
```
cd ~/catkin_ws/src
git clone git@github.com:imrasp/kalibr_allan.git
catkin_make_isolated -C ~/catkin_ws
```
source
```
cd ~/catkin_ws/
source devel_isolated/setup.bash
```

# Run
```
rosrun bagconvert bagconvert imu.bag /imu0
```

**source command should be complete with the same terminal**
