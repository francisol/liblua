cmake_minimum_required(VERSION 3.10)
project(liblua)

set(CMAKE_CXX_STANDARD 11)
include_directories(.)
aux_source_directory(. SRC)
add_library(lua ${SRC})