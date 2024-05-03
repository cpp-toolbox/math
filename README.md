# Info

Contains basic mathematical tools that are useful in other subprojects

# Dependencies

- [glm](https://github.com/g-truc/glm)

# CMake

```
...
# GLM: opengl mathematics
include_directories(external_libraries/glm)
add_subdirectory(external_libraries/glm)

... 

target_link_libraries(your_project_name ...)
```
