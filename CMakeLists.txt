add_library(gl3w_lib src/gl3w.c include/GL/gl3w.h include/GL/glcorearb.h include/KHR/khrplatform.h)
target_include_directories(gl3w_lib
    PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include
)
target_link_libraries(gl3w_lib OpenGL::GL OpenGL::GLU)
