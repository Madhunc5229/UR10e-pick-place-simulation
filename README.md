# UR10e-pick-place-simulation
Pick and Place simulation with UR10e robot manipulator.

Tools used:
SolidWorks, Python, Gazebo, RViz

Instructions to run the package:

Clone the repository into you catkin workspace:
git clone https://github.com/Madhunc5229/UR10e-pick-place-simulation

UR10e_SoildWorks_models directory contains all the SolidWorks models used to export the URDF file.

Build the package using catkin_make or catkin_build
source bash: source devel/setup.bash

To launch the project:
roslaunch ur10e ur10e.launch

To perform the pick and place operation:
Go to the scripts folder in the package:
cd src/ur10e/scripts

Run the following command to simulate pick and place operation:
pyhton3 manipulator_pickndplace.py

Run the following command to simulate robot drawing star:
pyhton3 manipulator_star.py
