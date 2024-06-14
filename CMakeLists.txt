cmake_minimum_required(VERSION 3.0.0)

project(TorizonDockerCppCMakeProjectTemplate VERSION 1.0 LANGUAGES CXX C)

add_executable(TorizonDockerCppCMakeProjectTemplate src/main.cpp)

set(CMAKE_SYSTEM_NAME Linux)

set_target_properties(TorizonDockerCppCMakeProjectTemplate PROPERTIES
    RUNTIME_OUTPUT_DIRECTORY "bin"
    ARCHIVE_OUTPUT_DIRECTORY "lib"
    LIBRARY_OUTPUT_DIRECTORY "lib"
)
