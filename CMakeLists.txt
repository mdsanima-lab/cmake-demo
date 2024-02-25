# Copyright (c) 2024 MDSANIMA LAB. All rights reserved.
# Licensed under the MIT license

cmake_minimum_required(VERSION 3.22)

set(CMAKE_CXX_STANDARD           20)
set(CMAKE_CXX_STANDARD_REQUIRED  ON)
set(CMAKE_CXX_EXTENSIONS        OFF)

project(mdsanima VERSION 0.1.0)

add_executable(${PROJECT_NAME}-awesome example/mdsanima-awesome/src/main.c)
add_executable(${PROJECT_NAME}-fantastic example/mdsanima-fantastic/src/main.cc)
add_executable(${PROJECT_NAME}-remarkable example/mdsanima-remarkable/src/main.cpp)