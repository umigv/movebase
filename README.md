# movebase
This repository is for running the navigation stack


To start the navigation stack: 
  Having roscore running in one terminal
  open up a new terminal
  type $roslaunch my_robot_configuration.launch
  open up a new terminal
  type $rosrun gmapping slam_gmapping scan:=scan
    #could be more elegant
   open up a new terminal
  type $roslaunch move_base.launch
  
