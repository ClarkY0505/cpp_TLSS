add_library(common_lib STATIC common.cpp)
target_link_libraries(common_lib PUBLIC Threads::Threads yaml-cpp)
