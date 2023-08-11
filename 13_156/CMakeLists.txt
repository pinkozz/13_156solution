cmake_minimum_required(VERSION 3.26)
project(Challenge)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Challenge
        main.cpp
        Movie.cpp
        Movie.h
        Movies.cpp
        Movies.h)
