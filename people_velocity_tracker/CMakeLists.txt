cmake_minimum_required(VERSION 2.8.3)
project(people_velocity_tracker)

catkin_python_setup()
catkin_package()
find_package(catkin REQUIRED COMPONENTS
  geometry_msgs
  people_msgs
)

install(DIRECTORY launch/
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)

