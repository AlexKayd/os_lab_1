cmake_minimum_required(VERSION 3.10)
project(osi_1)

set(CMAKE_CXX_STANDARD 17)

add_executable(main main.cpp)
add_executable(child child.cpp simple.cpp)