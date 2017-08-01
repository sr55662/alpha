cmake_minimum_required(VERSION 2.8.9)
project(alpha)

include_directories(include)

file(GLOB SOURCES "*/*.cpp" )
add_executable(alpha  ${SOURCES})
