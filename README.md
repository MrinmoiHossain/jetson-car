Jetson Autonomous RC Car
========================
Autonomous RC Race Car using ROS and Keras/TensorFlow. Inspired by JetsonHacks

<p align="center">
<img src="https://github.com/dat-ai/jetson-car/raw/master/docs/img/jetson-car.jpg" width="720">
</p>

Repository Contents
-------------------
* **`/docs`** - research papers, documents, photos related to this project
* **`/setup`** - Firmwares for Teensy 3.2 & SparkFun IMU Sensor + Set up instructions for Jetson TK1
* **`/src`** - ROS source directory (ROS Nodes and Launch files)

System Architecture
-------------------
<p align="center">
<img src="https://github.com/dat-ai/jetson-car/raw/master/docs/architecture.png" width="640">
</p>


Installation Guide:
-------------------
Please check [`setup/README.md`](./setup/README.md)

### How to use
--------------

* Open a new terminal
```shell
roscore
```

* Open another new terminal
```shell
roslaunch controller manual.launch
```

* From Joystick, press Right Trigger button to activate Autopilot 
* In order to stop, press the small Right button to stop Autopilot


### Author(s):
--------------
* [**Dat Nguyen**](https://github.com/dat-ai)
* I am very happy if anyone would like to work with me on this project. please shoot me an email at tdat.nguyen93@gmail.com

### Acknowledgements:
---------------------
* [JetsonHacks](http://www.jetsonhacks.com/) website provides helpful tips and tricks to work with Jetson TK1. JetsonHacks nicely simplifies the installation process with many ready-to-use scripts
* [DuckieTown](http://duckietown.mit.edu), an MIT Course,  is a great place to learn about developing autonomous vehicles.
* UPenn F1/10 Tutorials give a nice introduction to ROS, Hardware installation, and System Architecture for RC Car.
