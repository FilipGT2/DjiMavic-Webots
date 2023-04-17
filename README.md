# Dji Drone Simulation in Webots

This repository contains a simulation environment for Dji drones using Webots. The environment includes a simulated drone model and a physics engine for simulating flight dynamics.

Requirements:
Webots (R2021a or newer)
Python (3.7 or newer)
C++

Installation
Clone this repository:
$ git clone https://github.com/FilipGT2/DjiMavic-Webots.git

Open Webots and set the project path to the root directory of the repository.
Run the install_dependencies.py script to install the required Python packages:

shell
    $ cd dji-drone-simulation-webots
    $ python install_dependencies.py

Usage

Launch the simulation environment by opening the worlds/dji_drone.wbt file in Webots and clicking on the "Run" button.

You can control the drone using the dji_drone_controller.py Python script, which uses the Webots Python API. For example, you can take off the drone with the following command:
$ python dji_drone_controller.py --takeoff

Contributing

Pull requests and bug reports are welcome! If you want to contribute to this repository, please fork the repository and create a new branch for your changes. When you're ready to submit your changes, create a pull request to merge your branch into the main branch of this repository.
