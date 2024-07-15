# Install ROS1 and ROS2
Ensure you have ROS 1 installed on your system. If you haven't installed it yet, you can follow [the official ROS installation guide](http://wiki.ros.org/ROS/Installation).

# Install Turtlesim Package:
Make sure the Turtlesim package is installed. You can install it using the following command:
```
sudo apt-get install ros-noetic-turtlesim
```
> [!NOTE]
> Replace noetic with your ROS distribution if you're using a different version (e.g., melodic, kinetic).

# Initialize ROS:
Source your ROS setup file to set up the environment:
```
source /opt/ros/noetic/setup.bash
```
<img src= "https://github.com/user-attachments/assets/bca0d927-9473-488e-9cbb-665d02d715c7" alt= "image" width= 700>

# Start ROS Master:
Launch the ROS Master by running:
```
roscore
```
<img src= "https://github.com/user-attachments/assets/8184bfe2-27a6-4642-959c-d923a5cfd4bc" alt= "image" width= 700>

# Launch Turtlesim:
Open a new terminal, source the setup file, and launch Turtlesim:
```
source /opt/ros/noetic/setup.bash
rosrun turtlesim turtlesim_node
```

<img src= "https://github.com/user-attachments/assets/a5430c60-1a1d-4c06-9ace-a0f6298347cc" alt= "image" width= 700>

# Control the Turtle:
You can control the turtle using the turtle_teleop_key node. Open a new terminal, source the setup file, and run:
```
source /opt/ros/noetic/setup.bash
rosrun turtlesim turtle_teleop_key
```
> [!NOTE]
> Use the arrow keys to move the turtle around.


