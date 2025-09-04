cmake_minimum_required(VERSION 3.5.0)
project(my_math VERSION 1.0.0)
add_subdirectory(core)
add_subdirectory(print)
add_executable(calculator
main.cpp)
target_link_libraries(calculator calculate print)