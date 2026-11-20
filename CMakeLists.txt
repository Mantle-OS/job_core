cmake_minimum_required(VERSION 3.16)
project(JobCore
    VERSION 0.0.1
    LANGUAGES CXX
)

## build time deps
include(cmake/build_deps.cmake)

add_subdirectory(libs)
enable_testing()
add_subdirectory(tests)
# add_subdirectory(docs)
