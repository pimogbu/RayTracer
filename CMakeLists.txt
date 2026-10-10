cmake_minimum_required(VERSION 3.16)

project(RayTracer CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(RayTracer main.cc)

target_include_directories(RayTracer PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})