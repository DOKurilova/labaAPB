cmake_minimum_required(VERSION 2.8.11)

project(labaGit)

#set(CMAKE_INCLUDE_CURRENT_DIR ON)
#set(CMAKE_AUTOMOC ON)
set(CMAKE_BUILD_TYPE Debug)

set(CMAKE_CXX_STANDARD 17)

set (CXXFLAGS "-Wall -Wextra")
set (CMAKE_CXX_FLAGS "${CXXFLAGS}")

set(INCLUDE_DIRS
    "./Lib"
)

include_directories(${INCLUDE_DIRS})

set(SOURCES
    ./main.cpp
    ./Lib/sort.cpp

    )

set(HEADERS
	
    )

add_executable(${PROJECT_NAME} ${SOURCES} ${HEADERS} )

