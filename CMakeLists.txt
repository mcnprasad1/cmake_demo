cmake_minimum_required(VERSION 3.12)

set(CMAKE_CXX_COMPILER "C:/TCC/Tools/greenhills_ifx/comp_201815_4fp_WIN64/cxtri.exe")
set(CMAKE_C_COMPILER "C:/TCC/Tools/greenhills_ifx/comp_201815_4fp_WIN64/cctri.exe")

project(MyFirstProject)


add_executable(${PROJECT_NAME} main.cpp)
