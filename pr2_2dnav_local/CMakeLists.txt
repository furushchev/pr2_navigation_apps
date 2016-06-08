cmake_minimum_required(VERSION 2.8.3)
project(pr2_2dnav_local)

find_package(catkin REQUIRED)

catkin_package(
    CATKIN_DEPENDS pr2_navigation_perception pr2_navigation_local pr2_navigation_teleop pr2_machine
)

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
