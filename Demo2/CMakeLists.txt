cmake_minimum_required(VERSION 3.10)
project(Demo2)

set(CMAKE_CXX_STANDARD 11)

# 查找目录下的所有源文件
# 并将名称保存到 DIR_SRCS 变量
aux_source_directory(. DIR_SRCS)

add_executable(Demo2 ${DIR_SRCS})