list(APPEND src_sources "${CMAKE_CURRENT_SOURCE_DIR}/GeometryLibrary.cpp")
list(APPEND src_sources "${CMAKE_CURRENT_SOURCE_DIR}/GeometryLibrary.hpp")

list(APPEND src_includes "${CMAKE_CURRENT_SOURCE_DIR}")

set(src_sources ${src_sources} PARENT_SCOPE)
set(src_headers ${src_sources} PARENT_SCOPE)
set(src_includes ${src_sources} PARENT_SCOPE)