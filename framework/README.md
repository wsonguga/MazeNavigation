## Quick Start Guide
Run in CORE   - Quick Guide
First make sure that CORE has been installed. If you have not installed CORE, follow CORE Tutorial to install.
Also, Install python3-tk:
$ sudo apt-get install python3-tk
Download the Micromouse framework from Micrmouse Github Page. 
$ cd ~
$ git clone https://github.com/wsonguga/MazeNavigation.git
$ cd Micromouse
 
Configure the CORE environment for running core_demo.py
$ sudo ./setCORE.sh
 
If you encounter any problems running the above script, you may need to manually configure the environment for CORE.
Open the framework/gui.py before starting a session:
$ cd framework
$ python3 gui.py
 
Open CORE to demonstrate:
$ core-gui
 
Then open maze.xml, click the Start button.


## Module Description
    framework                   //framework written in Python3
    ├── controller.py           //Base class of MotorController and SensorController
    ├── controller_core.py      //MotorController and SensorController for CORE
    ├── controller_ev3.py       //MotorController and SensorController for EV3-Lego
    ├── demo_core.py            //Example of demonstrating multi-agent DFS in CORE
    ├── demo_ev3.py             //Example of demonstrating multi-agent DFS in EV3-Lego robot
    ├── gui.py                  //GUI program showing the discovery of micromouse in real maze
    ├── map.py                  //Contains the classes of Map and Cell
    ├── mouse.py                //The Micromouse class for managing all the modules
    ├── network.py              //Network Interface for communications between Micromice
    ├── strategy.py             //Strategy class
    ├── strategy_multidfs.py    //Example of multi-DFS Strategy implemented by the framework
    └── README.md

## Tutorial
Refer to [Tutorial](https://eniacluo.github.io/Micromouse/guide/tutorial.html).

## Demonstrations
Refer to [Demonstrations](https://eniacluo.github.io/Micromouse/guide/tutorial.html#demonstrations).

## API Documentation
Refer to [API Documentation](https://eniacluo.github.io/Micromouse/modules/docs.html).

## Architecture Description
Refer to [Architecture Description](https://docs.google.com/document/d/1im-nFw-iO0sKvpq5XH-agR5obBuFwbSLMbefUWsbebQ/edit#).
