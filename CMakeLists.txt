cmake_minimum_required(VERSION 3.17)
project(beginning_linux_programming C)

set(CMAKE_C_STANDARD 99)

add_executable(beginning_linux_programming chapter01/hello.c chapter01/fred.c chapter01/bill.c chapter01/lib.h chapter01/program.c)