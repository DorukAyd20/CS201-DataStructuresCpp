cmake_minimum_required(VERSION 3.24)
project(StructuresC__)

set(CMAKE_CXX_STANDARD 17)

add_library(StructuresC__ library.cpp src/Node.cpp src/Node.h src/LinkedLists.cpp src/LinkedLists.h)
