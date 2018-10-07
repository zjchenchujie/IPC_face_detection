cmake_minimum_required(VERSION 3.12)
project(aia_face_cmake)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(testProgs)

set(CMAKE_CXX_FLAGS "-Wall -fPIC -g -std=c++11")
set(CMAKE_C_FLAGS "-m64 -fPIC -O0 -Wall -g")
