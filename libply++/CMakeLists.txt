cmake_minimum_required(VERSION 2.8)
project(libplypp)
add_definitions("-std=c++11")

include_directories(${PROJECT_SOURCE_DIR})
add_executable(${PROJECT_NAME} libply++.cpp)
