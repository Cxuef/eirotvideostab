cmake_minimum_required(VERSION 2.8)
project (videoStabdemo)
find_package(OpenCV REQUIRED)
add_executable(videoStabdemo videostab.cpp)
target_link_libraries(videoStabdemo ${OpenCV_LIBS})

