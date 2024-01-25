cmake_minimum_required(VERSION 3.7)

project(PNGHide)

add_executable(pnghide src/main.cc)
#target_link_libraries(sandy ${SDL2_LIBRARIES})
set_target_properties(pnghide PROPERTIES
	CXX_STANDARD 17
	CXX_STANDARD_REQUIRED YES
	CXX_EXTENSIONS NO
)