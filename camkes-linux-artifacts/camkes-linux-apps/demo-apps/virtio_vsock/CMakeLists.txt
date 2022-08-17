#
# Copyright 2022, UNSW (ABN 57 195 873 179)
#
# SPDX-License-Identifier: BSD-2-Clause
#

cmake_minimum_required(VERSION 3.8.2)

project(virtiovsock C)

add_executable(virtiovsock virtiovsock.c)
target_link_libraries(virtiovsock -static-libgcc -static)
