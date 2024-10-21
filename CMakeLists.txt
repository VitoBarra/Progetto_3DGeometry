cmake_minimum_required(VERSION 3.28)
project(Progetto_3DGeometry)

set(CMAKE_CXX_STANDARD 26)

#find_package(Eigen REQUIRED)

add_executable(${CMAKE_PROJECT_NAME} "Prof code/esercizzi/simple_main_V0_BasicLoading.cpp")
target_include_directories(${CMAKE_PROJECT_NAME} PRIVATE vcglib vcglib/eigenlib )

