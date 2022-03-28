cmake_minimum_required(VERSION 3.12)
project(stbiw LANGUAGES CXX)

if (NOT CMAKE_BUILD_TYPE)
    set(CMAKE_BUILD_TYPE Release)
endif()

add_library(stbiw empty.cpp)

target_include_directories(stbiw
	PUBLIC
	${CMAKE_CURRENT_SOURCE_DIR})

