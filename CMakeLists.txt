cmake_minimum_required(VERSION 3.14)
project(pcsort)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -mtune=native -march=native")

add_executable(pcsort sort.cpp)
