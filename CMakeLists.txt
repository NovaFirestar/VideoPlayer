cmake_minimum_required(VERSION 3.5)

project(videoPlayer VERSION 1.0)

find_package(SDL2 REQUIRED)

add_executable(VideoPlayer
      main.cpp
      src/window.cpp
)





