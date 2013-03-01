cmake_minimum_required(VERSION 2.6)
project(testbin C)
add_executable(hello hello.c)

# find_path(TESTLIB_INCLUDE_DIR who.h HINTS ${TESTLIB_PREFIX}/include)
# find_library(TESTLIB_LIBRARY who HINTS ${TESTLIB_PREFIX}/lib)
# include_directories(${TESTLIB_INCLUDE_DIR})
# target_link_libraries(hello ${TESTLIB_LIBRARY})

install(TARGETS hello
        DESTINATION bin)
