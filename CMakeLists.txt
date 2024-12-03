cmake_minimum_required(3.29 VERSION)
project(untitled)

include(cmake/CPM.cmake)

add_executable(${CMAKE_PROJECT_NAME} main.cpp)
