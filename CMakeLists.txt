cmake_minimum_required(VERSION 3.4)
project(untitled20)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp adir/test.cpp Bdir/test1.cpp)
add_executable(untitled20 ${SOURCE_FILES})