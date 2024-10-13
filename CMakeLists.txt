cmake_minimum_required(VERSION 3.10)

project(hello_world)
set(CMAKE_BUILD_TYPE Release)

add_executable(main main.cpp hello/hello.cpp world/world.cpp)

target_include_directories(main PUBLIC hello world)