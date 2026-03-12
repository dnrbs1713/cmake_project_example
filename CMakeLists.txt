cmake_minimum_required(VERSION 3.13)

set(PROJECT_NAME cmake_project_example)
project(${PROJECT_NAME})

set(CMAKE_CXX_STANDARD 17)

add_executable(${PROJECT_NAME} src/main.cpp)