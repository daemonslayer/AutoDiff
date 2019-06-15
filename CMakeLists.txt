cmake_minimum_required(VERSION 3.10 FATAL_ERROR)
project(AutoDiff VERSION 0.0.1 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CONFIGURATION_TYPES Debug RelWithDebInfo CACHE STRING "")
set(DEBUG_CONFIGURATIONS Debug)

add_subdirectory(source)