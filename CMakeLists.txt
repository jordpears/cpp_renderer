cmake_minimum_required(VERSION 3.13)

project(cpp_renderer)

set(CMAKE_CXX_STANDARD 14)

add_executable(renderer src/main.cpp src/file_handlers/tgaimage.cpp src/file_handlers/tgaimage.h)