cmake_minimum_required(VERSION 3.8)
project(camera_calibration)

set(CMAKE_CXX_STANDARD 11)
set (OpenCV_DIR /opt/ros/kinetic/share/OpenCV-3.2.0-dev/)
find_package(OpenCV REQUIRED)
set(SOURCE_FILES main.cpp)

add_executable(camera_calibration ${SOURCE_FILES})
include_directories(${OpenCV_INCLUDE_DIRS})
target_link_libraries( camera_calibration ${OpenCV_LIBS} )