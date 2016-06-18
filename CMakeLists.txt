if(MSVC)
  cmake_minimum_required(VERSION 3.4)
else()
  cmake_minimum_required(VERSION 3.0)
endif()
project(tinyspline)

# Turn on folders
set_property(GLOBAL PROPERTY USE_FOLDERS ON)

add_subdirectory(library)
add_subdirectory(examples)
