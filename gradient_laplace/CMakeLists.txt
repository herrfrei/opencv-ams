cmake_minimum_required(VERSION 2.8)
project( Laplace )
find_package( OpenCV REQUIRED )
add_executable( Laplace Laplace_Demo.cpp )
target_link_libraries( Laplace ${OpenCV_LIBS} )
