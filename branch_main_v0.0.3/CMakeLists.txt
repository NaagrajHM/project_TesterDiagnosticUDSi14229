cmake_minimum_required(VERSION 3.10)

project(TesterDiagnosticUDSi14229_v0.0.3)

add_executable(b_${PROJECT_NAME}
	source/Application/Application.cpp
	source/ClassCore/ClassCore.cpp
)

target_include_directories(b_${PROJECT_NAME} PRIVATE
	source/InterfaceCore
)

