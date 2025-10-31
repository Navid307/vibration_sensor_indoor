cmake_minimum_required(VERSION 3.20.0)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})

project(vibration_sensor_indoor)

target_sources(app PRIVATE src/main.c)
