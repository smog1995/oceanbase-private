add_subdirectory(ob_error)
add_subdirectory(ob_admin)
add_subdirectory(upgrade)
if(OB_BUILD_CLOSE_MODULES)
  add_subdirectory(agentserver EXCLUDE_FROM_ALL)
  add_subdirectory(ob_bench EXCLUDE_FROM_ALL)
endif()
