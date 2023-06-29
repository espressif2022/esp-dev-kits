idf_component_register(
    SRCS "esp32-c3-lcdkit.c"
    INCLUDE_DIRS "include"
    PRIV_INCLUDE_DIRS "priv_include"
    PRIV_REQUIRES
        "esp_lcd"
    REQUIRES
        "driver"
        "spiffs"
)