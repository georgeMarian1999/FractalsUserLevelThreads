cmake_minimum_required(VERSION 3.24)
project(FractalsUserLevelThreads C)

set(CMAKE_C_STANDARD 11)

add_executable(FractalsUserLevelThreads main.c thread.h)
