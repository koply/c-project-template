cmake_minimum_required(VERSION 3.10.2)

project(cproj)

file(GLOB_RECURSE SRC_FILES src/*.c)
add_executable(${PROJECT_NAME} ${SRC_FILES})

target_include_directories(${PROJECT_NAME} PRIVATE include)
