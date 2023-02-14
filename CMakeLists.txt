file(GLOB STB_SRC *.c)

add_library(stb ${STB_SRC})

target_include_directories(stb
    PUBLIC
    ./)