cmake_minimum_required(VERSION 3.0)

aux_source_directory(. SRC_LIST)

add_executable(ChatClient ${SRC_LIST})


target_link_libraries(ChatClient pthread)