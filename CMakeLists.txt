cmake_minimum_required(VERSION 3.5.0)
project(raytracing VERSION 0.1.0 LANGUAGES C CXX)

add_executable(raytracing main.cpp)

include(CTest)
enable_testing()

