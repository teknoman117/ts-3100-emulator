cmake_minimum_required(VERSION 3.14)
project(kvm-emulator VERSION 0.1 LANGUAGES C CXX)

option(VIRTUAL_DISK "Enable a virtual C: drive" OFF)

add_subdirectory(src)