cmake_minimum_required(VERSION 3.11)

project(AdaptiveMultigridSolvers VERSION 10.02 LANGUAGES CXX)

# Force C++11 mode
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(Src)
