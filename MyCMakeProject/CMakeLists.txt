cmake_minimum_required(VERSION 4.0.3)
project(MyCMakeproject VERSION 0.1.0 LANGUAGES C CXX)

include(CTest)
enable_testing()

add_executable(MyCMakeproject mycppcode.cpp)

set_property(TARGET MyCMakeproject PROPERTY CXX_STANDARD 17)