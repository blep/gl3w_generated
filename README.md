# gl3w_generated

Generated source for CMake using [gl3w](http://github.com/skaslev/gl3w), Simple OpenGL core profile loading

## Integrating in your project

Integrates as a git submodule in your project tree, then in your top level `CMakeLists.txt` where you specify all dependencies:

```
find_package(OpenGL REQUIRED)

add_subdirectory( thirdparties/gl3w_generated )
```

The project is tagged after the date when it was generated:
- 2020.03.26
