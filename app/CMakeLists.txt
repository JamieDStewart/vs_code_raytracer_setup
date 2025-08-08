add_executable(RayTracer 
                src/main.cpp)

target_link_libraries(RayTracer PRIVATE libMath)

target_include_directories(RayTracer PRIVATE 
                        ${CMAKE_SOURCE_DIR}/libMath/include 
                        ${CMAKE_SOURCE_DIR}/app/include)