    zephyr_library()

    zephyr_library_sources(src/paw32xx.c)
    zephyr_library_include_directories(${CMAKE_SOURCE_DIR}/include)