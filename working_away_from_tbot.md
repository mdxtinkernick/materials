Working away from the turtlebot

Create a ROS package to put your code and files in. 
Create a repo in codebase and put your package in it, do regular commits (with good commit messages) to demonstrate your activity and progress.

Put the tutorial files in that package as you work on things.



Write a launch file to launch the python pub and sub examples, and remap the topic.

Change the example python pub and sub nodes in the tutorials to create a new node that subscribes to one topic, and publish to a different topic.

The most common pattern is that your node will subscribe to a topic, and use the data that it gets from that topic, perform a calculation of some sort, and publish the results on a different topic.
