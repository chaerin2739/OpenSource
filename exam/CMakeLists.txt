cmake_minimum_required(VERSION 3.0.2)
project (Mymain)

set ( PROJECT_LINK_LIBS libreverseCopy.so)
link_directories (/home/ycr/opensource/exam/lib_build)
include_directories (/home/ycr/opensource/exam)
add_executable(main_for_so main.c)
target_link_libraries(main_for_so ${PROJECT_LINK_LIBS} )

