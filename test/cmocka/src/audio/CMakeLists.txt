add_subdirectory(buffer)
add_subdirectory(component)
add_subdirectory(mixer)
add_subdirectory(pipeline)
if(CONFIG_COMP_VOLUME)
	add_subdirectory(volume)
endif()
