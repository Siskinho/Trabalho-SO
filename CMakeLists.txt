cmake_minimum_required(VERSION 3.15)
project(untitled2)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled2 Simulator.cpp Process.cpp Kernel.cpp Scheduler.cpp Cpu.cpp Core.cpp)