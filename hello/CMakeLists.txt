cmake_minimum_required(VERSION 3.16)
project(hello)

set(HELLO_SRC ${CMAKE_CURRENT_SOURCE_DIR}/hello.cpp)

add_library(hellolib ${HELLO_SRC})
