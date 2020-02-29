cmake_minimum_required(VERSION 3.11...3.16)

project(sstcam-install-test)

find_package(sstcam-common)

add_executable(test src/test_executable.cc )
target_link_libraries(test sstcam_descriptions)