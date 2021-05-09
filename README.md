
### [simulation] Exoskeleton control sketch

To start a gazebo scene

```bash
roslaunch profi2021_master_scene start_scene.launch
```

To start a control algorithm

```bash
roslaunch profi2021_master_solution solution.launch
```

To start controllers

```bash
 rosservice call /iiwa/controller_manager/switch_controller "{start_controllers: ['joint1_torque_controller'], stop_controllers: ['joint1_position_controller'], strictness: 1}"
 ```

 ```bash
 rosservice call /iiwa/controller_manager/switch_controller "{start_controllers: ['joint1_torque_controller'], stop_controllers: ['joint1_position_controller'], strictness: 1}"
 ```