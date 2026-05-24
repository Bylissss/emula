file(GLOB SOURCES "src/*.c")
add_subdirectory(vendor/SDL)
add_subdirectory(vendor/libemula)
add_executable(emula ${SOURCES})
