cmake_minimum_required(VERSION 2.8)

project(test_pcl)

find_package(PCL 1.7 REQUIRED)

include_directories(${PCL_INCLUDE_DIRS})
add_executable(${PROJECT_NAME} src/main.cpp)
target_link_libraries (${PROJECT_NAME}
    ${PCL_LIBRARIES}
 )
