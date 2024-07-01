add_library(macro-logger INTERFACE)

# Specify the include directories for the interface library
target_include_directories(macro-logger INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}
)