cmake_minimum_required(VERSION 3.27)
project(Library_)

set(CMAKE_CXX_STANDARD 17)

add_executable(Library_ main.cpp
        Book.h
        Book.cpp
        VipBook.h
        VipBook.cpp
        Person.h
        Person.cpp
        Staff.cpp
        Staff.h
        Member.cpp
        Member.h
        VipMember.h
        VipMember.cpp
        Library.cpp
        Library.h)
