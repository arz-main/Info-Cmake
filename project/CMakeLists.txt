cmake_minimum_required(VERSION 3.15)
project(HelloWorld)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)

# Include headers
include_directories(include)

# Add executable
add_executable(helloworld src/main.cpp)
