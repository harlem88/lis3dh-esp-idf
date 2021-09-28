set(lis3dh_srcs "src/lis3dh.c")

idf_component_register(SRCS "${lis3dh_srcs}"
        INCLUDE_DIRS "include"
        PRIV_REQUIRES esp8266_wrapper)