# Intelligens_szamitasi_modszerek

Open 2 terminal and navigate them into the root directory of this project.


In the 1st terminal type these commands in the following order:
1. colcon build
2. source /opt/ros/foxy/setup.bash
3. . install/local_setup.bash
4. ros2 launch learning_tf2_py turtle_tf2_demo.launch.py


In the 2nd terminal:
1. source /opt/ros/foxy/setup.bash
2. ros2 run turtlesim turtle_teleop_key


Now you can move the turtle in the 2nd terminal using the arrow keys and the other turtle will chase it which speed depends on the distance between the 2 turtles.