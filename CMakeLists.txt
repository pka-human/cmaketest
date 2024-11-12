cmake_minimum_required(VERSION 3.15)
project(MyProject C)

set(CMAKE_C_COMPILER "clang")

add_subdirectory(lib)

add_subdirectory(src)