cmake_minimum_required(VERSION 3.17)
project(tiny-mqtt C)

add_executable(tiny-mqtt client.c client.h mqtt.c mqtt.h client_test.c)
target_link_libraries(tiny-mqtt ws2_32)
