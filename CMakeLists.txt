cmake_minimum_required(VERSION 3.6)
project(KochCurve)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(KochCurve ${SOURCE_FILES})
target_link_libraries(KochCurve graph)