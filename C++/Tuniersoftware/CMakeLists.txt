cmake_minimum_required(VERSION 3.5)

project(Tuniersoftware LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Tuniersoftware main.cpp)

install(TARGETS Tuniersoftware
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
