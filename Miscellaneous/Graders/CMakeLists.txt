cmake_minimum_required(VERSION 2.8)
project(Graders)

set (Graders_VERSION_MAJOR 1)
set (Graders_VERSION_MINOR 0)
add_compile_options (-std=c++0x)

add_executable(graders graders.cpp)

