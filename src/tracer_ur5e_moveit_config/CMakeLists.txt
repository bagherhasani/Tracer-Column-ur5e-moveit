cmake_minimum_required(VERSION 3.0.2)
project(tracer_ur5e_moveit_config)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
) 