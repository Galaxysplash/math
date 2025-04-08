cmake_minimum_required(VERSION 3.30)
project(Math)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(src)

add_executable(Math)

target_sources(Math 
    src/main.cpp

)