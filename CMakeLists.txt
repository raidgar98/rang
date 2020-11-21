cmake_minimum_required (VERSION 3.1)
project (rang CXX)

add_library( rang src/rang.cpp )
target_include_directories( rang PUBLIC include )
install(FILES ${PROJECT_SOURCE_DIR}/include/rang.hpp DESTINATION include)
