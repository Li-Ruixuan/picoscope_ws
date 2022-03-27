# picoscope_ws

This repo contains orocos component to start picoscope data logging. 

It is developed in ROS1 + Orocos1. Please Use the  following instruction:


1) you have to compile it by using "catkin_make"




2) In the first terminal

source devel/setup.bash

roslaunch etasl_application_template load_setup_picoscope.launch


3) In second termianl
 
source devel/setup.bash

cd src/etasl_application_template/scripts/deploy

rttlua -i  test_picoscope.lua
