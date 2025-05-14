cmake_minimum_required(VERSION 3.10)
project(my_project)
include_directories(include)
set(SOURCES
    src/main.cpp
    src/math.cpp
    src/input_output.cpp
)
add_executable(MyExecutable ${SOURCES})
