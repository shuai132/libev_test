cmake_minimum_required(VERSION 3.13)

project(libev_test)

set(CMAKE_CXX_STANDARD 14)

#file(GLOB SRCS libev-4.33/*.c)
add_executable(${PROJECT_NAME} main.cpp ${SRCS})
target_link_libraries(${PROJECT_NAME} ev)
