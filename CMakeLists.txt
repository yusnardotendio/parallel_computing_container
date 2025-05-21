cmake_minimum_required(VERSION 3.10)
project(parallel_computing_container)

# Set C++ standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(parallel_computing_container src/simple.cpp)