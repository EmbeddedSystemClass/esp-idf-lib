idf_component_register(
    SRCS "led_strip_spi.c" "led_strip_spi_sk9822.c"
    INCLUDE_DIRS .
    REQUIRES log led_effect esp_idf_lib_helpers
)
