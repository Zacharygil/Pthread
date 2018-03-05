cmake_minimum_required(VERSION 3.6)
project(eecs678_pthreads_intro_lab)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
    ptcount_atomic.c
    ptcount_mutex.c)

add_executable(eecs678_pthreads_intro_lab ${SOURCE_FILES})