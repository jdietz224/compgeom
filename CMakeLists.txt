add_library(compgeom ${CMAKE_CURRENT_SOURCE_DIR}/include/vec3.h ${CMAKE_CURRENT_SOURCE_DIR}/include/color.h)
set_target_properties(compgeom PROPERTIES LINKER_LANGUAGE CXX)
target_include_directories(compgeom INTERFACE ${CMAKE_CURRENT_SOUR}/include)
