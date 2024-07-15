# SPDX-License-Identifier: MIT

list(APPEND EXTRA_DTC_FLAGS "-qq")

zephyr_library()
zephyr_library_include_directories(${CMAKE_SOURCE_DIR}/include)