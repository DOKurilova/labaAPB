cmake_minimum_required(VERSION 2.8.11)

project(labaGit)

set(CMAKE_INCLUDE_CURRENT_DIR ON)
set(CMAKE_AUTOMOC ON)
set(CMAKE_BUILD_TYPE Debug)

set(CMAKE_CXX_STANDARD 17)

set (CXXFLAGS "-Wall -Wextra")
set (CMAKE_CXX_FLAGS "${CXXFLAGS}")

include_directories(${INCLUDE_DIRS})

set(SOURCES
    ./main.cpp
    )

add_executable(${PROJECT_NAME} ${SOURCES} ${HEADERS} )

