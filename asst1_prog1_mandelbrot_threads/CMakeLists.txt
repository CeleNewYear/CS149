cmake_minimum_required(VERSION 3.10)

# set the project name
project(prog1)

# CXX=g++ -m64
set(CMAKE_CXX_FLAGS "-m64")

# CXXFLAGS=-I../common -Iobjs/ -O3 -std=c++11 -Wall -fPIC
set(CMAKE_CXX_FLAGS "-I../common -Iobjs/ -O3 -std=c++11 -Wall -fPIC")

# 查询当前目录下所有源文件
aux_source_directory(. DIR_SRCS)

# add the executable
add_executable(prog1 ${DIR_SRCS})
