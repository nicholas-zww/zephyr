# SPDX-License-Identifier: Apache-2.0

if(CONFIG_CPU_AARCH32_CORTEX_A OR CONFIG_CPU_AARCH32_CORTEX_R)
  zephyr_include_directories(${ZEPHYR_CURRENT_MODULE_DIR})
endif()
