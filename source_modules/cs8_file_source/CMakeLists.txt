cmake_minimum_required(VERSION 3.13)
project(cs8_file_source)

file(GLOB SRC "src/*.cpp")

include(${SDRPP_MODULE_CMAKE})

target_include_directories(cs8_file_source PRIVATE "src/")