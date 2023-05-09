cmake_minimum_required(VERSION 3.0.0)
project(actions-cpp)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

file(GLOB_RECURSE SOURCES "src/*.cpp")

add_executable(actions-cpp ${SOURCES})


