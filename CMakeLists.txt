set(COMPONENT_SRCS "")
set(COMPONENT_ADD_INCLUDEDIRS "include")

register_component()

component_get_target(TARGET GSL)
set_target_properties(${TARGET} PROPERTIES INTERFACE_COMPILE_OPTIONS -std=c++17)
