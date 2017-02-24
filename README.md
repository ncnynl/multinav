# multinav
multi point navigation by turtlebot

How to run:


 - new windows:

roslaunch turtlebot_bringup minimal.launch

 - new windows:

roslaunh turtlebot_navigation amcl_demo.launch map_file:=/home/nc/map/map.yaml  

 - replace map of you . 

 - new windows:

roslaunch turtlebot_rviz_launchers view_navigation.launch

 - look at the newest information in RVIZ

 - new windows:

rosrun multinav nav.py

 - please chmod +x nav.py first.
 - set loations[] in your nav.py for where to nav , several point you want to go .
 - now , set init pose in rviz , it will go .


