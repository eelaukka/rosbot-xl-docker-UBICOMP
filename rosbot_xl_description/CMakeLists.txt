cmake_minimum_required(VERSION 3.10.2)
project(rosbot_xl_description)

find_package(ament_cmake REQUIRED)

install(DIRECTORY
  meshes
  urdf
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
