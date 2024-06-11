# Build
```bash
mkdir jaguar_ws
cd jaguar_ws
git clone https://github.com/wust-dcr/jaguar_4x4_ros src/

source /opt/ros/noetic/setup.bash 
catkin_make

# Ignore the errors. The messages has to be likned. Try again
source devel/setup.bash
catkin_make
```

# Run 

## Driver

```bash
source devel/setup.bash
ROS_MASTER_URI=http://localhost:11311/

roscore 
```

```bash
source devel/setup.bash
ROS_MASTER_URI=http://localhost:11311/

rosrun drrobot_jaguar4x4_player drrobot_jaguar4x4_player_node
```

## Teleop
```bash
source devel/setup.bash
ROS_MASTER_URI=http://localhost:11311/

rosrun drrobot_jaguar4x4_player drrobot_jaguar4x4_keyboard_teleop_node
```