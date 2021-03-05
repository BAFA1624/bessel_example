cmake_minimum_required(VERSION 3.14)
project(BesselExample)

set(GCC_COVERAGE_COMPILE_FLAGS "-Wall -Wextra -pedantic -O3 -lm")

add_executable(test example.c)


