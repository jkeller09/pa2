cmake_minimum_required(VERSION 3.3)
project(pa2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp Clusters.cpp Clusters.h Point.cpp Point.h)
add_executable(pa2 ${SOURCE_FILES})