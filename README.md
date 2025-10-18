Using The construct website, I wrote the following commands to enable me to display and control the robot arm:
sudo apt install git
sudo apt install python3-colcon-common-extensions
sudo apt install ros-humble-moveit
source /opt/ros/humble/setup.bash
mkdir -p ~/ros2_ws/src
cd ~/ros2_ws/src
git clone https://github.com/smart-methods/Robot_Arm_ROS2.git
cd ..
Colcon build
source ~/ros2_ws/install/setup.bash# Robot_Arm
