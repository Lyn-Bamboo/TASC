# TASC

This repository contains the code used to reproduce the results presented in the paper "Decentralized Multi-Agent Planning Using Model Predictive Control and Time-Aware Safe Corridors".

The repository has been tested on Ubuntu 20.04 (ROS noetic). The backend optimizer is Gurobi. Please install the [Gurobi Optimizer](https://www.gurobi.com) (free academic lisence available).

Run this commands:

```bash
git clone https://github.com/Lyn-Bamboo/TASC.git
cd TASC
catkin build
source devel/setup.bash
roslaunch planner swarm.launch   
```

## Reference

[1] C. Toumieh and A. Lambert, "Decentralized Multi-Agent Planning Using Model Predictive Control and Time-Aware Safe Corridors," in IEEE Robotics and Automation Letters, vol. 7, no. 4, pp. 11110-11117, Oct. 2022.

