cmake_minimum_required(VERSION 2.6.0)

# Use your own vmelib
add_library(vmelib vmelib/vmelib.cpp vmelib/include/vmelib.h) 

add_executable(jDAQLite jDAQLite.cpp)
target_link_libraries(jDAQLite vmelib)


 

