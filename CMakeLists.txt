
cmake_minimum_required(VERSION 3.9)

project(elfio CXX)

if (NOT TARGET elfio)

	add_library(elfio INTERFACE)
	target_include_directories(elfio SYSTEM INTERFACE ${PROJECT_SOURCE_DIR}/include/)

endif()
