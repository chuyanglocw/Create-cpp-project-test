cmake_minimum_required(VERSION 3.16)

project(hello_world)

add_subdirectory(hello)
add_subdirectory(world)

add_executable(main main.cpp)

target_link_libraries(main PUBLIC hellolib)
target_link_libraries(main PUBLIC worldlib)