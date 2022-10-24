add_library (metal-cpp INTERFACE)

target_include_directories(metal-cpp INTERFACE
    "metal-cpp"
)

set_property(TARGET metal-cpp PROPERTY CXX_STANDARD 17)
