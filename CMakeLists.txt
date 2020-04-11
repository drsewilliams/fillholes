
cmake_minimum_required(VERSION 2.8)
 
PROJECT(FillHoles)
 
find_package(VTK REQUIRED)
include(${VTK_USE_FILE})
 
add_executable(FillHoles MACOSX_BUNDLE FillHoles.cxx )
 
target_link_libraries(FillHoles ${VTK_LIBRARIES})
