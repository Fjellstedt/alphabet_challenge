cmake_minimum_required(VERSION 3.0.0)
project(asteroids VERSION 0.1.0)

include(CTest)
enable_testing()

add_executable(asteroids WIN32 src/main.c)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
