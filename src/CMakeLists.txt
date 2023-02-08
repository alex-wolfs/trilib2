cmake_minimum_required(VERSION 3.1)
project(trilib2 C)

include(${CMAKE_BINARY_DIR}/sources.cmake)
include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_library(trilib2 ${HEADERS} ${SOURCES})
