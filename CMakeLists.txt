cmake_minimum_required(VERSION 3.5.0)
project(Game VERSION 0.1.0)

add_executable(CPP_Game main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_NAME ${PROJECT_VERSION})
include(CPack)