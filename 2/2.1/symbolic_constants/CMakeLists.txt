cmake_minimum_required(VERSION 3.19)
project(symbolic_constants C)

set(CMAKE_C_STANDARD 99)

add_executable(symbolic_constants main.c
        ../2-float/main.c)