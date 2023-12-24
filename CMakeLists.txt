# FILEPATH: /Users/bautista_garcia/programming/raytracingow/CMakeLists.txt

# Set the minimum required CMake version
cmake_minimum_required(VERSION 3.12)

# Set the project name
project(raytracing VERSION 0.1.0 LANGUAGES CXX)

# Add the source files
set(SOURCES
    src/main.cc
)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include_directories(../)

# Add the executable target
add_executable(raytracingow ${SOURCES})
