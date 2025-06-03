cmake_minimum_required(VERSION 3.5)

project(videoPlayer VERSION 1.0)

find_package(SDL2 REQUIRED)

add_executable(VideoPlayer
      main.cpp
      src/window.cpp
)

#Add the include directories and link libraries here
target_include_directories(VideoPlayer
PUBLIC ${SDL2_INCLUDE_DIR}
}

target_link_libraries(VideoPlayer
SDL2::SDL2
}



