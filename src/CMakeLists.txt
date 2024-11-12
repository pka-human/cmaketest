set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)
add_executable(MyExecutable main.c)
target_link_libraries(MyExecutable MyLibrary)
target_include_directories(MyExecutable PRIVATE ${CMAKE_SOURCE_DIR}/lib)