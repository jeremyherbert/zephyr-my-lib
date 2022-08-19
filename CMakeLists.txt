if(CONFIG_MY_LIB)
  zephyr_include_directories(
    ${ZEPHYR_MY_LIB_MODULE_DIR}/src
  )

  zephyr_library()
  zephyr_library_sources(
    ${ZEPHYR_MY_LIB_MODULE_DIR}/src/my_lib.c
  )
endif()
