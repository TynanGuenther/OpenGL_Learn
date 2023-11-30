cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(LearnOpenGL VERSION 1.0)
file(GLOB_RECURSE SRC_FILES src/*.cpp CONFIGURE_DEPENDS)
add_executable(LearnOpenGL main.cpp)
