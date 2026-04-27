cmake_minimum_required(VERSION 3.10)

project(TesterDiagnosticUDSi14229_v0.0.4)

add_executable(b_${PROJECT_NAME}
	source/ServicesSystemEcuM/ClassServicesSystemEcuM.cpp
	source/DeviceDriverEthernet/ClassDeviceDriverEthernet.cpp
)

target_include_directories(b_${PROJECT_NAME} PRIVATE
	source/DeviceDriverEthernet
	source/ServicesSystemEcuM
	source/ServicesSystemSchM
)

