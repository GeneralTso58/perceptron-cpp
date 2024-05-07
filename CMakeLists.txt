cmake_minimum_required(VERSION 3.19.3)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

project(perceptrons)

add_executable(Main src/main.cpp)

target_include_directories(Main PRIVATE "include/")