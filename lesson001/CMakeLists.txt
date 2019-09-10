cmake_minimum_required(VERSION 2.8)
project(lesson001)
include_directories(~/Projects/glad/include)
set(sources main.cpp
	glad.c
	)
add_executable(${PROJECT_NAME} ${sources})
target_link_libraries(${PROJECT_NAME} glfw GL dl)
