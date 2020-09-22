file(GLOB_RECURSE C_SOURCES ./*.c)
file(GLOB_RECURSE ASM_SOURCES ./*.s)

add_executable(main ${C_SOURCES} ${ASM_SOURCES})

