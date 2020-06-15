# ROS-Installation-

## Step 1: 
#### Download VirtualBox. https://www.virtualbox.org/wiki/Downloads
## Step 2: 
#### Download Ubuntu 20.04 LTS. https://ubuntu.com/download/desktop

### **Note: You have to make sure that "Recommended system requirements" are qualified with your PC.**
#### This Video for the first two steps for more clarification. https://www.youtube.com/watch?v=x5MhydijWmc

## Step 3:
####  Open Ubuntu and go to Terminal or (Ctrl+Alt+t).
## Step 4:
#### Copy the line below and paste it in the Terminal.
     wget -c https://raw.githubusercontent.com/qboticslabs/ros_install_noetic/master/ros_install_noetic.sh && chmod +x ./ros_install_noetic.sh && ./ros_install_noetic.sh
#### After few seconds will ask you "Enter your install (Default is 1)". Press 1 and wait until it's done.
## Step 5:
#### To check that you have installed ROS Noetic write down. 
       rosversion -d
#### If it shows.  _noetic_
#### Then, well done you have downloaded ROS Noetic!
