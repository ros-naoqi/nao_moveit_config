cmake_minimum_required(VERSION 2.8.3)
project(nao_moveit_config)

find_package(catkin REQUIRED)

catkin_package()

install(FILES .setup_assistant DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY config DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
