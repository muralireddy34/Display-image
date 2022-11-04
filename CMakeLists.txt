cmake_minimum_required(VERSION 2.8)
project( Display-image )
add_executable( Display-image src/Displayimage.cpp )
target_link_libraries( Display-image ${OpenCV_LIBS} )
