cmake_minimum_required(VERSION 3.15)
project(DataStructure C)

set(CMAKE_C_STANDARD 99)

include_directories(
        ${CMAKE_CURRENT_SOURCE_DIR}/googletest/googletest/includ
)

add_subdirectory(./googletest/googletest)

add_executable(DataStructure main.c func.h)