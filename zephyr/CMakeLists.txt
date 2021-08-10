zephyr_sources(
    ../scd4x_i2c.c
    ../sensirion_common.c
    ../sample-implementations/zephyr_user_space/sensirion_i2c_hal.c
    ../sensirion_i2c.c
)

zephyr_include_directories(..)