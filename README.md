
### [simulation] Exoskeleton control sketch

#### Requirenments

##### ros-noetic

```
sudo apt install -y ros-noetic-kdl-parser-py 
```



To start a gazebo scene

```bash
roslaunch exoskeleton_scene start_scene.launch
```

To start a control algorithm

```bash
roslaunch safety_control start.launch
```

To start controllers

```bash
 rosservice call /iiwa/controller_manager/switch_controller "{start_controllers: ['joint1_torque_controller'], stop_controllers: ['joint1_position_controller'], strictness: 1}"
 ```

 ```bash
 rosservice call /iiwa/controller_manager/switch_controller "{start_controllers: ['joint1_torque_controller'], stop_controllers: ['joint1_position_controller'], strictness: 1}"
 ```