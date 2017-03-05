cmake_minimum_required(VERSION 3.6)
project(mp03)

set(SOURCE_FILES
        tsh.c)

add_executable(mp03 ${SOURCE_FILES})

set_property(TARGET mp03 PROPERTY C_STANDARD 90)
