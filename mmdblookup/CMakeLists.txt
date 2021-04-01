cmake_minimum_required(VERSION 3.17)
project(mmdblookup C)

set(CMAKE_C_STANDARD 90)

add_executable(mmdblookup main.c)

target_link_libraries(mmdblookup maxminddb)