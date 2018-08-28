cmake_minimum_required(VERSION 3.2)

project(atosl)

include_directories(include)
set(SRC src/atosl.c src/macho.c src/converter.c)

set(CMAKE_BUILD_TYPE DEBUG)
#ADD_DEFINITIONS(-DDEBUG)
add_executable(${PROJECT_NAME} ${SRC})
