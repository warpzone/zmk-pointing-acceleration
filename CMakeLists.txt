
target_sources(app PRIVATE src/input_processor_accel.c)
target_include_directories(app PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/dts/bindings)
