cmake_minimum_required(VERSION 3.28)
project(connect++)

file(GLOB_RECURSE sources src/*.cpp src/*.h)

add_executable(connect++ ${sources})
