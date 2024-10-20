cmake_minimum_required(VERSION 3.11)
project (raylib-lua-sol LANGUAGES C CXX)

if (MSVC)
	add_compile_options("/bigobj")
else()
	add_compile_options("-mbig-obj")
endif()

add_subdirectory(include)
