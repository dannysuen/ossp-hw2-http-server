cmake_minimum_required(VERSION 3.5)
project(berkeley_cs162_hw2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu99")

set(SOURCE_FILES libhttp.c httpserver.c)
add_executable(berkeley_cs162_hw2 ${SOURCE_FILES})