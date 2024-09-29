cmake_minimum_required(VERSION 3.29)
project(lab10)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(lab10
    exp.cpp
    exp.h
    main.cpp
    parser.cpp
    parser.h
    scanner.cpp
    scanner.h
    token.cpp
    token.h
    visitor.cpp
    visitor.h)
