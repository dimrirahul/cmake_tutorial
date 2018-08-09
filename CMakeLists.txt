cmake_minimum_required (VERSION 3.10)

set(CMAKE_CXX_COMPILER "/usr/bin/clang++-6.0")
set(CMAKE_CXX_FLAGS "-g -Wall")

project(UrlShortener)

add_subdirectory(src)
#add_subdirectory(bin)
