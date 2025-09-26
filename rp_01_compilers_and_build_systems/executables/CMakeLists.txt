# TODO: compile executable that will be run
add_executable(mini_core
    many_object_in_stack_example.cpp
)
# TODO: link the executable against the core_library

target_link_libraries(mini_core
    core_library
)