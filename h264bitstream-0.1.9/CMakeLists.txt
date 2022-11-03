cmake_minimum_required(VERSION 3.6)

project(h264bitstream)

set(source_files h264_avcc.c
    h264_sei.c
    h264_stream.c)

add_library(h264bitstream ${source_files})
