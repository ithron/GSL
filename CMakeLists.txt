set(COMPONENT_SRCS "")
set(COMPONENT_ADD_INCLUDEDIRS "include")

register_component()

set_target_properties(GSL PROPERTIES INTERFACE_COMPILE_OPTIONS -std=c++17)

