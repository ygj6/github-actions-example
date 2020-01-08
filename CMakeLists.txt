cmake_minimum_required(VERSION 3.2)

cmake_policy(SET CMP0074 NEW)
project(verify)

set(CMAKE_VERBOSE_MAKEFILE 1)

add_executable(main main.c)

enable_testing()
add_test(main main)

