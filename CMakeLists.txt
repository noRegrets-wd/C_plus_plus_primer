cmake_minimum_required(VERSION 3.15)
project(C__)

set(CMAKE_CXX_STANDARD 14)

add_executable(C__ main.cpp test.cpp test.h)
add_executable(io_test test.cpp)