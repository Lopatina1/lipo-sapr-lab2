cmake_minimum_required(VERSION 3.12)
project(lipo_sapr_lab2)

set(CMAKE_CXX_STANDARD 14)

include_directories(src/ErrorFinder)
include_directories(src/ErrorFinderTest)

add_executable(lipo_sapr_lab2
        src/ErrorFinder/ErrorFinder.cpp
        src/ErrorFinder/ErrorFinder.h
        src/ErrorFinderTest/ErrorFinderTest.cpp
        src/ErrorFinderTest/ErrorFinderTest.h
        src/main.cpp)
