cmake_minimum_required(VERSION 3.22.0)

project(task_2)

find_package(Catch2 3 REQUIRED)
add_executable(task_2 task_2.cpp)
target_link_libraries(task_2 PRIVATE Catch2::Catch2)