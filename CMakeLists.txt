cmake_minimum_required(VERSION 3.0.0)

project(Magma VERSION 0.1.0 LANGUAGES C CXX)

include_directories(headers)

add_executable(Magma ./src/Main.cpp  ./src/App.cpp)
target_include_directories(Magma PRIVATE ./headers)