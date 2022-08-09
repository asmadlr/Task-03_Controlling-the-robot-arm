![‏‏لقطة الشاشة (43)](https://user-images.githubusercontent.com/108361853/183736514-16ff47a2-0f86-4625-97d4-51b79f309bfe.png)
# Controlling the robot arm by Moveit and kinematics

URDF, meshes, configuration files etc. for the ABB IRB1600ID industrial robot

Also see the irb1600id moveit configuration that references this

` $ roslaunch moveit_pkg demo.launch `

You can also connect with hardware by running:

` $ rosrun rosserial_python serial_node.py _port:=/dev/ttyUSB0 _baud:=115200 `

(Note: You may need to use ttyACM)

Run the following instruction to use gazebo

` $ roslaunch moveit_pkg demo_gazebo.launch `

