# Controlling the robot arm by Moveit and kinematics

URDF, meshes, configuration files etc. for the ABB IRB1600ID industrial robot

Also see the irb1600id moveit configuration that references this

On https://github.com/smart-methods/arduino_robot_arm


` $ roslaunch moveit_pkg demo.launch `

You can also connect with hardware by running:

` $ rosrun rosserial_python serial_node.py _port:=/dev/ttyUSB0 _baud:=115200 `

(Note: You may need to use ttyACM)

Run the following instruction to use gazebo

` $ roslaunch moveit_pkg demo_gazebo.launch `


![‏‏لقطة الشاشة (43)](https://user-images.githubusercontent.com/108361853/183736870-c512bf1a-861a-4ae6-9ad8-a98e9e6aec5c.png)

![‏‏لقطة الشاشة (42)](https://user-images.githubusercontent.com/108361853/183737546-3495ccf0-30f9-4463-8f77-561f79104093.png)


![‏‏لقطة الشاشة (41)](https://user-images.githubusercontent.com/108361853/183737596-8f553726-d1a6-40e4-96bd-36224ab4a253.png)


