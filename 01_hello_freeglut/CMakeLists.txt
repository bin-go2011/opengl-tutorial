add_executable(01_hello_freeglut main.cpp LUtil.cpp)
target_link_libraries(01_hello_freeglut ${OPENGL_LIBRARIES} glut)