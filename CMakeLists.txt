cmake_minimum_required(VERSION 3.21)

project(HycFrame
    VERSION 1.0
    DESCRIPTION "for rendering."
    LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

set_property(GLOBAL PROPERTY USE_FOLDERS ON)

add_subdirectory(HycSamples)