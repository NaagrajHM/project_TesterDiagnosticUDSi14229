cmake_minimum_required(VERSION 3.10)

project(TesterDiagnosticUDSi14229_v0.0.1)

# set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/build)

add_executable(${PROJECT_NAME}
	source/Application/Application.cpp
	source/ClassCore/ClassCore.cpp
)

target_include_directories(${PROJECT_NAME} PRIVATE
	source/InterfaceCore
)

