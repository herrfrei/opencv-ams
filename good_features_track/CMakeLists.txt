cmake_minimum_required(VERSION 2.8)
project( GFTT )
find_package( OpenCV 3.0.0 EXACT REQUIRED )
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable( GFTT goodFeaturesToTrack.cpp )
target_link_libraries( GFTT ${OpenCV_LIBS} )
