# idf_component_register(SRCS "cmd_system.c"
#                     INCLUDE_DIRS .
#                     REQUIRES console spi_flash driver)
# 兼容性更新
idf_component_register(SRCS "cmd_system.c"
                    INCLUDE_DIRS .
                    REQUIRES console spi_flash driver esp_hw_support esp_system)