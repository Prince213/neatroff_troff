cmake_minimum_required(VERSION 3.0)
project(pic C)
add_executable(pic picy.c picl.c main.c print.c misc.c symtab.c blockgen.c boxgen.c circgen.c arcgen.c linegen.c movegen.c textgen.c input.c for.c pltroff.c)
install(TARGETS pic)
