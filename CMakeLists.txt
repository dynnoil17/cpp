cmake_minimum_required(VERSION 3.6)
project(first)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES headers/square.h source/square.cpp source/main.cpp source/stack.cpp headers/stack.h source/exercises.cpp headers/exercises.h headers/tests.h source/tests.cpp headers/examples.h source/examples.cpp source/persons.cpp headers/persons.h)
add_executable(first ${SOURCE_FILES})