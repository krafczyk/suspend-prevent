project(suspend-prevent)

cmake_minimum_required(VERSION 2.8)

add_subdirectory(bin)
add_subdirectory(systemd-services)
add_subdirectory(udev-rules)
