ADD_SUBDIRECTORY (bcg729 EXCLUDE_FROM_ALL)
INCLUDE_DIRECTORIES (bcg729/include)

set (g729_SRCS
  g729.c
)

SET(sems_module_name g729)
SET(sems_module_libs bcg729-static)

INCLUDE(${CMAKE_SOURCE_DIR}/cmake/module.rules.txt)
