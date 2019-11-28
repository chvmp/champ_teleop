cmake_minimum_required(VERSION 2.8.3)
project(champ_teleop)

find_package(catkin REQUIRED)

catkin_package()

catkin_install_python(PROGRAMS
   teleop.py
   DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)

