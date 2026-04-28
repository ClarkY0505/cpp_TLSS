add_library(monitor_lib STATIC monitoringSys.cpp)
target_link_libraries(monitor_lib PUBLIC common_lib rpc_lib proto_lib)
