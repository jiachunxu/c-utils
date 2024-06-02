cmake_minimum_required(VERSION 3.28)

project(c-utils C)

set(CMAKE_C_STANDARD 11)
add_executable(c-utils
        main.c
        any-head.h
)