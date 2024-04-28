add_library(operation STATIC addition.c subtraction.c division.c multiplication.c modulus.c) 
target_include_directories(operation INTERFACE ${CMAKE_HOME_DIRECTORY}includes/)
