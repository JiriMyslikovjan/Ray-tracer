project(ray_tracer)

add_library(stb INTERFACE)

target_include_directories(stb
    INTERFACE
        ${CMAKE_CURRENT_LIST_DIR}    
    )