add_library(libMath STATIC 
        src/MathUtil.cpp )

target_include_directories(libMath PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)