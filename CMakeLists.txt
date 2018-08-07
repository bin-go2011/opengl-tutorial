project(OpenGL_Tutorial)
cmake_minimum_required(VERSION 2.8)
find_package(OpenGL REQUIRED)
message(STATUS ${OPENGL_INCLUDE_DIR})
include_directories(
    ${OPENGL_INCLUDE_DIR}/Headers
    /usr/local/Cellar/freeglut/3.0.0/include/
)
link_directories(/usr/local/Cellar/freeglut/3.0.0/lib)
add_subdirectory(01_hello_freeglut)