# ROS2
Robot Operating System 
Follow https://docs.ros.org/en/jazzy/Installation.html
1. Using turtlesim, ros2 and rqt
2. 




## To use in WIndows
## Install WSL
Website: https://learn.microsoft.com/en-us/windows/wsl/install
1. Open Powershell in Admin Mode
2. Rul wsl --install
3. Restart
4. Run wsl --list --online to see available linux distros
5. Install distro wsl --install ubuntu-22.04
6. Create username and password.
7. verify version by running wsl -l -v. Should see version 2.
8. open ubuntu type code .

## Setup Github in WSL
1. Setup credentials
2. 
   
## ROS2 Humble Installation
1. Locale Installation
   > locale # check current locale setings
   > sudo apt update && sudo apt install locales
   > sudo locale-gen en_US en_US.UTF-8
   > sudo update-locale LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8
   > export LANG=en_US.UTF-8
   > locale # Confirm updated locale settings
3. Curl Installation and ROS Key
   > sudo rm /usr/share/keyrings/ros-archive-keyring.gpg
   > sudo curl -sSL https://raw.githubusercontent.com/ros/rosdistro/master/ros.key -o /usr/share/keyrings/ros-archive-keyring.gpg
