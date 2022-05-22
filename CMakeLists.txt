cmake_minimum_required(VERSION 3.18)

project(main CXX)

find_package(fmt REQUIRED)

add_executable(main main.cpp)
target_link_libraries(main PRIVATE fmt::fmt)

add_subdirectory(test)
