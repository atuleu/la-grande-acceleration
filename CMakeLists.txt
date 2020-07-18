project(la-grande-acceleration C CXX)

cmake_minimum_required(VERSION 3.11)

find_package(OpenCV REQUIRED core highgui)

add_subdirectory(src)
