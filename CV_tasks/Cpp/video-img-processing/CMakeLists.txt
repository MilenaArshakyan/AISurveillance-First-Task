cmake_minimum_required(VERSION 3.29.2)
project( Open_CV_Project )
find_package(OpenCV REQUIRED)
#include_directories( ${OpenCV_INCLUDE_DIRS} )
# add_executable( Open_CV_Project display_image.cpp )
# add_executable( Open_CV_Project display_video.cpp )
#add_executable( Open_CV_Project image_annotation.cpp )
#add_executable( Open_CV_Project image_manipulation.cpp )
#add_executable( Open_CV_Project color_spaces_image_filtering.cpp )
add_executable( Open_CV_Project real_time_video_processing.cpp )
target_link_libraries( Open_CV_Project  ${OpenCV_LIBS})