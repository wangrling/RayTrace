cmake_minimum_required (VERSION 3.5)

if (CMAKE_COMPILER_IS_GNUCXX)
    set(CMAKE_CXX_FLAGS "-std=c++11" ${CMAKE_CXX_FLAGS})
    message(STATUS "optional:-std=c++11")
endif(CMAKE_COMPILER_IS_GNUCXX)

add_executable(geometry geometry.cpp)

