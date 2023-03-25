
file(GLOB srcs
    "*.c"
    # "../components/lvlg/*.c"
)

# set(dirs
#     "."
#     "../components/lvgl"
# )


# set(files
#     "file/FP-button-sn-2245-merge.csv"
#     "file/FP-button-sn-2251-3-1671524466.csv"
#     "file/FP-button-sn-2251-3-1671526099.csv"
#     "file/FP-button-sn-2306-3-1675474406.csv"
#     "file/FP-button-sn-2307-3-1675972352.csv"
#     "file/FP-button-sn-2310-3-1677554725.csv"
#     "file/FP-button-sn-2311-3-1677563966.csv"
#     )

# set(files
#     "file/ltt01_keys_binary_20220829.bin"
#     )

# register_component()


# idf_component_register(SRCS ${srcs}
#                        EMBED_FILES  ${files}
#                        INCLUDE_DIRS ${dirs})

                       
# idf_component_register(SRCS ${srcs}
#                        INCLUDE_DIRS ${dirs})


# idf_component_register(SRCS main.c)
idf_component_register(SRCS ${srcs})
