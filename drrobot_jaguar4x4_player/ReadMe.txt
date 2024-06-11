This ROS sample code is for Jaguar4x4 robot(before 2014) mode from Dr Robot Inc.
By default, the robot IP is "192.168.0.60".
you need fix your Linux PC IP address as "192.168.0.104" after your PC is connected with robot.

Run main control node
	"rosrun jaguar_jaguar4x4_player drrobot_jaguar4x4_player_node"
To use the keyboard to contorl the robot

	"rosrun jaguar4x4_ drrobot_keyboard_teleop_node"
This program will use "WASD" key to move the robot, and release the key will stop the robot.

The source code will show you what sensor message topics the program will published and what control topic it will subscribe to receive the command.


