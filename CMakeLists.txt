cmake_minimum_required(VERSION 3.0)

project(HELLO)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(${PROJECT_SOURCE_DIR}/include)

add_executable(hello main.cpp src/hello.cpp)
