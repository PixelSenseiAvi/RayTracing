cmake_minimum_required(VERSION 3.16)

project(raytracing_app)
set(CMAKE_CXX_STANDARD 17)

add_executable(raytracing_app
    src/Renderer.cpp
	src/RayTracing.cpp
    src/Camera.cpp
)

target_link_libraries(raytracing_app walnut)