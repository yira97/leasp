cmake_minimum_required(VERSION 3.15)
project(leasp)
set(CMAKE_CXX_STANDARD 17)

include_directories(src/include)

add_executable(${PROJECT_NAME} src/main.cpp)