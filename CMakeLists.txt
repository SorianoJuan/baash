cmake_minimum_required(VERSION 3.8)
project(baash)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        archfunc.c
        archfunc.h
        evalfunc.c
        evalfunc.h
        main.c
        Makefile)

add_executable(baash ${SOURCE_FILES})