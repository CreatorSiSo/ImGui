cmake_minimum_required(VERSION 3.0)

project(imgui)

# Targets
add_library(
  ${PROJECT_NAME} STATIC ./imgui.cpp ./imgui_draw.cpp ./imgui_tables.cpp
                         ./imgui_widgets.cpp ./imgui_demo.cpp)

# Includes
target_include_directories(${PROJECT_NAME} PRIVATE ./)
