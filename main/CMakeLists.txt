file(GLOB srcs
    "*.c"
    "lvgl_app/*.c"
)

set(inc
    "."
    "lvgl_app"
)

set(components
    # "lvgl_esp32_drivers"
    # "lvgl_touch"
    # "lvgl_tft"
    # "lvgl"
    # "driver"
    )


idf_component_register(SRCS ${srcs}
                    INCLUDE_DIRS ${inc}
                    REQUIRES ${components})

target_compile_definitions(${COMPONENT_LIB} PRIVATE LV_CONF_INCLUDE_SIMPLE=1)
