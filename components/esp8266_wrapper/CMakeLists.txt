set(esp8266_wrapper_srcs "src/esp8266_wrapper.c")

idf_component_register(SRCS "${esp8266_wrapper_srcs}"
        INCLUDE_DIRS "include")