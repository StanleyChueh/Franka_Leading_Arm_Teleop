# F.L.A.T(Franka Leading Arm Teleop)
Leading arm teleoperation with Franka emika panda
1. Launch Franka-ROS joint impedance control
```
cd franka_ws/
source /opt/ros/noetic/setup.bash
roslaunch franka_example_controllers joint_impedance_example_controller.launch robot_ip:=172.16.0.2 load_gripper:=true
```
2. Run Leading arm control code
```
cd ~/gello_franka
python gello_franka_stable.py
```
