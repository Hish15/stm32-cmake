This is a simple blinky project

Multiple targets are handled : F1, F4 and/or L0. Those are handled in the CMakeLists.txt as option.

To use C++, the following changes must be done :
 1) Rename the blinky.c -> blinky.cpp
 2) In CMakeLists.txt add CXX in the project() function
 3) In CMakeLists.txt replace all `blinky.c` by `blinky.cpp` 
