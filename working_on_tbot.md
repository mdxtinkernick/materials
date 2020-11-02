Working on the turtlebot

Watch the video from last week to see how to launch the virtual machine and connect to the turtlebot.

Launch  minimal launch to get the turtlebot ready to move.

rosrun turtlebot_teleop turtlebot_teleop_key

Use rostopic, rqt_graph, rviz to introspect the system, and work out how you can remap topics to get the robot to move.

Once it is moving look at the 3dsensor launch example and use rviz to get some visual feedback from the robot.

If you have done those then look at the gmapping demo. The map is stored in ram while it is made, so you need to run the command to save it - do not save it in the tmp folder as they specify, as that is a temporary location for storing files, and they will be automatically deleted at times by the system.

http://wiki.ros.org/turtlebot_navigation/Tutorials/Build%20a%20map%20with%20SLAM

