project(fatfs)

set(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -O2")
        
add_library(fatfs STATIC ff.c ffunicode.c ffsystem.c)
