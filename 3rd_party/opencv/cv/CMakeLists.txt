CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

include_directories(include)
file(GLOB cv_src src/*.cpp)
add_library(cv STATIC ${cv_src})
# target_link_libraries(cv cxcore)

# include_directories(include)
# file(GLOB cxcore_src src/*.cpp)
# add_library(cxcore STATIC ${cxcore_src})
