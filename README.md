# MIPSIM

A program that takes in binary data inside a text file and returns the corresponding MIPs Processor assembly for that binary. It also simulates these commands and returns a log file showing how each instruction effected the processor as it was executed.

## Installation
1. clone this repository.
2. compile `MIPSsim.cpp` with the C compiler of your choice. For IOS users the proper command is `clang MIPSsim.cpp -o MIPSsim`

## Usage
To use the program provide the text file containing the binary data as an arugment. For example, the proper way to execute the program would be `./MIPSsim binaryfile.txt`
