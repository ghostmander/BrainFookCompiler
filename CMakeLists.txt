cmake_minimum_required(VERSION 3.22)
project(BrainFook_Compiler)

set(CMAKE_CXX_STANDARD 14)

add_executable(BrainFook_Compiler main.cpp brainfuckProcessor.h)
