CMAKE_MINIMUM_REQUIRED(VERSION 3.17.2)
PROJECT(dependency-A)

add_definitions("-std=c++11")

add_library(dependency-A STATIC something.cpp)
