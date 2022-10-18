cmake_minimum_required(VERSION 3.22.0)

project(task_1)

find_package(Catch2 3 REQUIRED)
add_executable(task_1 task_1.cpp)
target_link_libraries(task_1 PRIVATE Catch2::Catch2)