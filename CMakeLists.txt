cmake_minimum_required(VERSION 3.9)
project(hello)

set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${hello_SOURCE_DIR}/lib)

add_library(hello STATIC hello.cpp)