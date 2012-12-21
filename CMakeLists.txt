
cmake_minimum_required(VERSION 2.8)
set(CMAKE_MODULE_PATH ${CMAKE_CURRENT_SOURCE_DIR}/Modules)


set(CMAKE_CXX_FLAGS "-std=c++0x")

set(exec_name test)

link_libraries(
)

add_executable(${exec_name}
	main.cpp
)

target_link_libraries(${exec_name}
)

