#add_subdirectory (src)
include_directories (include)
aux_source_directory (./src source_list)
add_library (FUNC SHARED ${source_list})