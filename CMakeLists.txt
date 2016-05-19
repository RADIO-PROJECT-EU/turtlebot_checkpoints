cmake_minimum_required(VERSION 2.8.3)
project(turtlebot_checkpoints)

find_package(catkin REQUIRED COMPONENTS
  actionlib
  geometry_msgs
  move_base_msgs
  nav_msgs
  roscpp
  rospy
  tf
  visualization_msgs
)

#catkin_python_setup()

catkin_package(CATKIN_DEPENDS actionlib geometry_msgs move_base_msgs nav_msgs roscpp rospy tf visualization_msgs)
