set(COMPONENT_SRCS "")
set(COMPONENT_ADD_INCLUDEDIRS "include")

register_component()

target_set_property(GSL INTERFACE_COMPILE_OPTIONS -std=c++17)

