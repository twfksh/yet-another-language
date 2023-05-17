cmake_minimum_required(VERSION 3.25)
project(yal C)

set(CMAKE_C_STANDARD 17)

include_directories(.)

add_executable(yal
        chunk.c
        chunk.h
        common.h
        debug.c
        debug.h
        main.c
        memory.c
        memory.h
        value.h value.c vm.h vm.c)
