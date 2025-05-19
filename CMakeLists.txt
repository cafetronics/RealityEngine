cmake_minimum_required(VERSION 4.0)
list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake")

project("Reality Engine")

add_subdirectory("vendor")
add_subdirectory("src")