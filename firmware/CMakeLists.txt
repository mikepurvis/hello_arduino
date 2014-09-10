cmake_minimum_required(VERSION 2.8.3)

include_directories(${ROS_LIB_DIR})

generate_arduino_firmware(hello
  SRCS hello.cpp
  BOARD leonardo
  PORT /dev/ttyACM0
)
