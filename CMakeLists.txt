cmake_minimum_required(VERSION 3.17)

project(Sniffy VERSION 1.0)

add_executable(detector main.cpp Detector.h Function.h StringUtility.h)
set(CMAKE_EXE_LINKER_FLAGS "-static-libstdc++")
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)
add_compile_options(-Wall)
