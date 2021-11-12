cmake_minimum_required(VERSION 2.8.3)
project(freddy_description)

find_package(catkin REQUIRED)

catkin_package(
  CATKIN_DEPENDS
)

install(DIRECTORY meshes robots
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
