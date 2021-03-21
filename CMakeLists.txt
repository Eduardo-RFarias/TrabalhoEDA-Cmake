cmake_minimum_required(VERSION 3.0.0)
project(trabalhoEda VERSION 0.1.0)

add_subdirectory(lib)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/out)

add_executable(trabalhoEda main.c)

target_link_libraries(trabalhoEda lib)
