cmake_minimum_required(VERSION 3.17)
project(unix_shell_implementation)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(shell shell.c)