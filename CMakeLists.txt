project(raspicam_recorder)

find_package(catkin REQUIRED COMPONENTS
  raspicam_node
)

install(DIRECTORY
  launch
  config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)