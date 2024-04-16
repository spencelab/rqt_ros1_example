# rqt_ros1_example
Example minimal gui in ros 1 noetic tested in ubuntu 20 focal

Basically followed this page and various linked pages until got it to work:

https://wiki.ros.org/rqt

The version for ROS Noetic.

It would probably be smart to keep the GUI a separate node from functionality.

Eg it should just publish and subscribe, and do services and actions, and not 

a) handle serial port stuff
b) do other things

that can be done in other nodes. 
