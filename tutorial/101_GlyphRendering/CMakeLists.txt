cmake_minimum_required(VERSION 2.8.12)
project(101_GlyphRendering)

add_executable(${PROJECT_NAME}_bin main.cpp)
target_link_libraries(${PROJECT_NAME}_bin igl::core igl::opengl_glfw tutorials)
