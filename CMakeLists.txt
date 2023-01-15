cmake_minimum_required(VERSION 3.24)
project(ImageTransform)

set(CMAKE_CXX_STANDARD 20)

add_executable(ImageTransform main.cpp
               uiuc/RGB_HSL.h
               uiuc/PNG.cpp
               uiuc/PNG.h
               uiuc/HSLAPixel.cpp
               uiuc/HSLAPixel.h
               ImageTransform.h
               ImageTransform.cpp)

