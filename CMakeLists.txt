cmake_minimum_required(VERSION 2.8.9)
project (hello C)
add_executable(hello main.c)
install(TARGETS hello DESTINATION /usr/bin)
