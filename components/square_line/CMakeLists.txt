
file(GLOB_RECURSE SOURCES *.c)

file(GLOB srcs
    "*.c"
)


set(dirs
    "."
    # "include"
    # "../queue/include"
    # "../time_event/include"
    # "../packet_parser_fsm/include"
    # "../comm_handle/include"
)

idf_component_register(SRCS ${srcs}
                       INCLUDE_DIRS ${dirs}
                       REQUIRES lvgl
                       )

