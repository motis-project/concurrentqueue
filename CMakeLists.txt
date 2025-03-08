cmake_minimum_required(VERSION 3.10)
project(concurrentqueue)

add_library(concurrentqueue INTERFACE)
target_include_directories(concurrentqueue SYSTEM INTERFACE .)
