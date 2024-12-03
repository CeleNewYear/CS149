cmake_minimum_required(VERSION 3.10)

# set the project name
project(PROG2_VECINTRIN)

# 查询当前目录所有跟文件
aux_source_directory(. DIR_SRCS)

# add the executable
add_executable(proj2 ${DIR_SRCS}) 
