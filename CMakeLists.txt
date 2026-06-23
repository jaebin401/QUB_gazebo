cmake_minimum_required(VERSION 3.8)
project(QUB_gazebo)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY urdf meshes launch
  DESTINATION share/${PROJECT_NAME}
)

ament_package()