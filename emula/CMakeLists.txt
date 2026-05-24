file(GLOB SOURCES "src/*.c")
add_executable(emula ${SOURCES})

add_subdirectory(vendor/SDL)
target_include_directories(emula PUBLIC vendor/SDL/include)
add_subdirectory(vendor/libemula)
target_include_directories(emula PUBLIC vendor/libemula/include)
