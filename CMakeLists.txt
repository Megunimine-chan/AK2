cmake_minimum_required(VERSION 2.8)	
										

project(lab2_info)			

add_library(
	Library
	STATIC 
	Library.cpp
)	

add_executable(
	Main 
	Main.cpp
)	

target_link_libraries(Main Library)		

