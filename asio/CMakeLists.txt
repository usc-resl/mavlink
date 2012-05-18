include_directories(${Boost_INCLUDE_DIRS} ${CMAKE_BINARY_DIR}/include)
link_libraries(${Boost_LIBRARIES})

add_executable(blocking_udp_echo_client blocking_udp_echo_client.cpp)
add_executable(blocking_tcp_echo_client blocking_tcp_echo_client.cpp)
add_executable(async_echo_server async_echo_server.cpp)
