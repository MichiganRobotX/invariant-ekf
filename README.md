# inekf
This repository contains a C++ library that implements an invariant extended Kalman filter (InEKF) for aided inertial navigation. 

This filter can be used to estimate a robot's 3D pose and velocity using an IMU motion model for propagation. The following measurements are currently supported:
* Landmark position measurements
* Kinematic and contact measurements

The core theory was developed by Barrau and Bonnabel and is presented in:
["The Invariant Extended Kalman filter as a Stable Observer"](https://arxiv.org/abs/1410.1465).

Inclusion of kinematic and contact measurements is presented in:
["Contact-aided Invariant Extended Kalman Filtering for Legged Robot State Estimation"](https://arxiv.org/pdf/1805.10410.pdf).

A ROS wrapper for the filter is available at [https://github.com/RossHartley/invariant-ekf-ros](https://github.com/RossHartley/invariant-ekf-ros).

## Installation
TODO

## Examples
TODO

## Citations
The contact-aided invariant extended Kalman filter is described in: 
* R. Hartley, M. G. Jadidi, J. Grizzle, and R. M. Eustice, “Contact-aided invariant extended kalman filtering for legged robot state estimation,” in Proceedings of Robotics: Science and Systems, Pittsburgh, Pennsylvania, June 2018.
```
@INPROCEEDINGS{Hartley-RSS-18, 
    AUTHOR    = {Ross Hartley AND Maani Ghaffari Jadidi AND Jessy Grizzle AND Ryan M Eustice}, 
    TITLE     = {Contact-Aided Invariant Extended Kalman Filtering for Legged Robot State Estimation}, 
    BOOKTITLE = {Proceedings of Robotics: Science and Systems}, 
    YEAR      = {2018}, 
    ADDRESS   = {Pittsburgh, Pennsylvania}, 
    MONTH     = {June}, 
    DOI       = {10.15607/RSS.2018.XIV.050} 
} 
```
The core theory of invariant extended Kalman filtering is presented in:
* Barrau, Axel, and Silvère Bonnabel. "The invariant extended Kalman filter as a stable observer." IEEE Transactions on Automatic Control 62.4 (2017): 1797-1812.
```
@article{barrau2017invariant,
  title={The invariant extended Kalman filter as a stable observer},
  author={Barrau, Axel and Bonnabel, Silv{\`e}re},
  journal={IEEE Transactions on Automatic Control},
  volume={62},
  number={4},
  pages={1797--1812},
  year={2017},
  publisher={IEEE}
}
```
