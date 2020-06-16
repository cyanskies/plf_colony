project(plf-colony)
add_library(plf-colony INTERFACE)
target_sources(plf-colony INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/plf_colony.h)
target_include_directories(plf-colony INTERFACE ./)