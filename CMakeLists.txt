cmake_minimum_required(VERSION 3.28)
project(BESLE_v2_0)

set(CMAKE_CXX_STANDARD 17)

add_executable(BESLE_v2_0 Drivers/Tutorials/Box.cpp
        Drivers/Tutorials/Composite.cpp
        Drivers/Tutorials/Polycrystal.cpp
        Drivers/Tutorials/Vertebra2.cpp)
