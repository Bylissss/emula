file(GLOB SOURCES "src/*.c")
add_subdirectory(vendor/SDL)
add_executable(emula ${SOURCES})
include_directories(../libemula/src)
