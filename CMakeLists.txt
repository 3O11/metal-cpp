add_library (metal-cpp INTERFACE)
add_library (metal-cpp-extensions INTERFACE)

target_include_directories (metal-cpp INTERFACE
    "metal-cpp"
)

target_include_directories (metal-cpp-extensions INTERFACE
    "metal-cpp-examples"
)

set_property(TARGET metal-cpp PROPERTY CXX_STANDARD 17)
set_property(TARGET metal-cpp-extensions PROPERTY CXX_STANDARD 17)
