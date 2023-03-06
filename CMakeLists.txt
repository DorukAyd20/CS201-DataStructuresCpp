cmake_minimum_required(VERSION 3.24)
project(StructuresCpp)

set(CMAKE_CXX_STANDARD 17)

add_library(StructuresCpp library.cpp src/Node.cpp src/Node.h src/LinkedLists.cpp src/LinkedLists.h)
