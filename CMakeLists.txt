cmake_minimum_required(VERSION 3.5.1)

set(modules_path_new_value
    ${CMAKE_MODULE_PATH}
    "${CMAKE_CURRENT_SOURCE_DIR}/modules/")
set(CMAKE_MODULE_PATH "${modules_path_new_value}" CACHE STRING "" FORCE)