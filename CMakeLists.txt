cmake_minimum_required(VERSION 3.17)
project(socket C)

set(CMAKE_C_STANDARD 99)

add_executable(client client.c)
add_executable(server server.c)
add_executable(test test.c)