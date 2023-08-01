Code accompanying the thesis: 
HyREAL: On Hybrid Learning and Reasoning for Explainable and Safe Navigation of Autonomous Cars in Interactive POMDP

The code is based on the repository: https://github.com/dikshant2210/Carla-CTS02


#### Install CARLA

See here - https://carla.readthedocs.io/en/0.9.12/start_quickstart/

##### Important: The code is compatible with CARLA version 0.9.12

#### IS-DESPOT-p

1) A C++11-compatible compiler is required. IS-DESPOT-p has been developed using g++ 7.3.0. A newer version might work too.

    `sudo apt-get install build-essential `

2) Makefile

    `sudo apt-get install make`
   
3) Navigate to `/ISDESPOT/isdespot-ped-pred/is-despot/` and run `make`

4) Navigate to `ISDESPOT/isdespot-ped-pred/is-despot/problems/isdespotp_car` and run `make`. This will create a binary `car`.
