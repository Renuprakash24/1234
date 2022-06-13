
cmake_minimum_required(VERSION 3.16.3)

project(hello)

set_target_properties(PROPERTIES
    CXX_STANDARD 11
    CXX_STANDARD_REQUIRED ON

add_executable(app main.cpp)  
)



