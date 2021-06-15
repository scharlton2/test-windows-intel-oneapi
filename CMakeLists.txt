cmake_minimum_required(VERSION 3.12)

project(test-windows-intel-oneapi C CXX Fortran)

include(CTest)

add_subdirectory(cpp-hello)

add_subdirectory(fortran-hello)

