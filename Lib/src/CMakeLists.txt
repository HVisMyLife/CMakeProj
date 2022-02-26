include_directories(${CMakeProj_SOURCE_DIR}/Lib/inc)
file(GLOB all_SRC
     "*.c"
     "*.cpp"
)

add_library(Lib ${all_SRC})