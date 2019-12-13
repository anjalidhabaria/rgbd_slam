# rgbd_slam 
Dependencies rtabmap and rtabmap_ros  
Install turtlebot 3 dependencies by following - 
    $ sudo apt install ros-melodic-turtlebot3* ros-melodic-dwa-local-planner

Steps to run - 
    $ export TURTLEBOT3_MODEL=waffle
    $ roslaunch turtlebot3_gazebo turtlebot3_world.launch

    $ export TURTLEBOT3_MODEL=waffle
    $ roslaunch rtabmap_ros demo_turtlebot3_navigation.launch
