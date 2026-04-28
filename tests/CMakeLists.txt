add_executable(test_ftp_server test_ftp_server.cpp)
target_link_libraries(test_ftp_server
    ftp_lib
    common_lib
    GTest::GTest
    GTest::Main
)
add_test(NAME ftp_server_test COMMAND test_ftp_server)
