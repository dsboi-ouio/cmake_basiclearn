cmake_minimum_required(VERSION 3.11)

project(cmake_minimum_required)

include_directories(includes)

add_library(TOOLS_STATIC STATIC tools/hello.cpp)

add_executable(cmake_basiclearn_2 src/cmake_basiclearn.cpp)
target_link_libraries(cmake_basiclearn_2 PRIVATE TOOLS_STATIC)