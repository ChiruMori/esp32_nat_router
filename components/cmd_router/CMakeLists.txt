# idf_component_register(SRCS "cmd_router.c"
#                     INCLUDE_DIRS .
#                     REQUIRES console nvs_flash esp_wifi driver)
# 更新兼容性依赖
idf_component_register(SRCS "cmd_router.c"
                    INCLUDE_DIRS .
                    REQUIRES console nvs_flash esp_wifi driver esp_hw_support spi_flash)
