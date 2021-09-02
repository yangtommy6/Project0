cmake_minimum_required(VERSION 3.16.3)
project(Project0)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Project0
    Lab0PassOffCases/answer0.txt
    Lab0PassOffCases/answer1.txt
    Lab0PassOffCases/answer2.txt
    Lab0PassOffCases/answer3.txt
    Lab0PassOffCases/answer4.txt
    Lab0PassOffCases/answer5.txt
    Lab0PassOffCases/input0.txt
    Lab0PassOffCases/input1.txt
    Lab0PassOffCases/input2.txt
    Lab0PassOffCases/input3.txt
    Lab0PassOffCases/input4.txt
    Lab0PassOffCases/input5.txt
    Book.cpp
    Book.h
    BookCreator.cpp
    BookCreator.h
    BookListCreator.cpp
    BookListCreator.h
    Info.cpp
    Info.h
    Library.cpp
    Library.h
    main.cpp
    makefile_0
    README.md)
