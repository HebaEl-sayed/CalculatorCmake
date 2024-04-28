cmake_minimum_required (VERSION 3.2)
project(calculater
        DESCRIPTION "calculater project")


add_subdirectory(${CMAKE_HOME_DIRECTORY}/library)
add_executable(calculater main.c )
target_include_directories(calculater PRIVATE includies/)
target_link_libraries(calculater PUBLIC operation)



