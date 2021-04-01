cmake_minimum_required(VERSION 3.18)

project(Lab_1 VERSION 2.0)

add_executable(Lab_1 main.c)

configure_file(Lab_1_Config.h.in Lab_1_Config.h)

target_include_directories(Lab_1 PUBLIC
                           "${PROJECT_BINARY_DIR}"
                           )

