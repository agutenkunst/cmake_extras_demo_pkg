cmake_minimum_required(VERSION 2.8.3)
project(cmake_extras_demo_pkg)

find_package(catkin REQUIRED)
catkin_package(CFG_EXTRAS cmake_extras_demo_pkg-extras.cmake)

install(DIRECTORY cmake/Modules
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/cmake)
