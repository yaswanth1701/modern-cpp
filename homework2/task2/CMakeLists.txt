cmake_minimum_required(VERSION 3.10)
project(Hw2_task2)
set(CMAKE_INSTALL_PREFIX ${PROJECT_SOURCE_DIR})
add_executable(task2 src/task2.cpp)
install(TARGETS task2 DESTINATION ${CMAKE_INSTALL_PREFIX}/bin )
