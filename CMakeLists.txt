cmake_minimum_required(VERSION 3.15)

project(ThePankeyEngine_System_Hardware)

if(NOT TARGET ThePankeyEngine_System_Hardware)

    add_library(ThePankeyEngine_System_Hardware INTERFACE)

    target_include_directories(
        ThePankeyEngine_System_Hardware
        INTERFACE
            ${CMAKE_CURRENT_SOURCE_DIR}
    )

endif()
