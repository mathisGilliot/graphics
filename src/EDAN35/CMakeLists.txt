cmake_minimum_required (VERSION 3.0)

set (
	PROJECT_SOURCES

	"main.cpp"
	"main.hpp"
)

source_group (
	EDAN35${PATH_SEP}Project

	FILES
	${PROJECT_SOURCE_DIR}/main.cpp
	${PROJECT_SOURCE_DIR}/main.hpp
)

luggcgl_new_assignment ("EDAN35_Project" "${PROJECT_SOURCES}" "")
