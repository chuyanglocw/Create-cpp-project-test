cmake_minimum_required(VERSION 3.16)
project(hello)

set(WORLD_SRC ${CMAKE_CURRENT_SOURCE_DIR}/world.cpp)

add_library(worldlib ${WORLD_SRC})