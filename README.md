# Joy-of-Pokemon-Observation

## Problem Overview

The **Pokémon Conservation Society** is studying Pokémon species and their habitats around the globe. Each habitat contains a number of Pokémon species, and researchers know how many limbs each species has. The total number of limbs for a habitat is also known, but not the exact combination of species. The problem asks us to determine how many different ways the species' limb counts can sum up to the observed total number of limbs in each habitat.

## Problem Statement

Given several habitats, each with a total number of limbs **t** and several species with known limb counts, we need to determine how many different ways we can combine the species to form the exact total number of limbs.

### Input variables

1. An integer `h` representing the number of habitats.
2. For each habitat:
   - An integer `t` representing the total number of limbs in the habitat.
   - An integer `s` representing the number of species in the habitat.
   - A list of `s` integers representing the number of limbs for each species.
## Prerequisites

Before you start, ensure that you have the following installed:

- **g++ (GNU Compiler Collection)**: The program uses `g++` to compile the code.
- **make**: To automate the compilation process using a Makefile.

If you don't have `g++` or `make` installed, you can install them via MinGW or another compiler for Windows.

## Project Setup

Follow these steps to set up and run the program on your local machine:

### 1. Clone the Repository

If you haven't already cloned the repository, do so using the following Git command:

```
git clone <repository-url>
cd <repository-folder>
```

### 2. Compile the Program

Open a Command Prompt/termial in visual studio and navigate to the folder containing the program files.

```
D:\trail> make
This will invoke the Makefile and use g++ to compile the pokemon_1.cpp file into an executable called program.exe.
```
### 3 Run the Program
After compiling the program, you can run it by executing the following command:
```
D:\trail> .\program.exe
```
### 4. Provide Input
When you run the program, it will prompt for input values. For example, you may input the following:
Example input:

```
3 6 1 3 6 2 2 3 6 3 1 2 3
```

### Output

The program will process the input and give you the following output:

```
1
2
7
```



![image](https://github.com/user-attachments/assets/8b7868fc-d454-481b-a1dc-7cc9e5b63d1b)



## Compiler Selection in Makefile:
CC = g++: The Makefile specifies that we are using g++ as the C++ compiler.
CFLAGS = -Wall -std=c++11: This sets the flags for the compiler:
-Wall enables all warnings to help identify potential issues.
-std=c++11 specifies the C++11 standard to be used for compiling.
### Input Format

### Alternative Method: Online Compiler

If you prefer not to set up the environment locally, you can simply run the program on an online compiler such as [GDB Online Compiler](https://www.jdoodle.com/c-online-compiler).



### Notes

- For large data  input sets like:

  ```
  4 1000000000 3 1 1 1 0 3 2 4 5 17 2 2 4 34 3 5 3 2
  ```

  The program may not produce an output on some online compilers (e.g., GDB).



### resource usage 
 The program takes approximately **1 second** to compile, and for larger data, it may take **2 to 3 seconds** in Visual Studio Code/local pc setup 

## Memory Usage

The program uses **XXX MB** of memory during execution.

## Conclusion


![image](https://github.com/user-attachments/assets/223190a3-b691-4c71-8475-0afcbf93ad2d)


```
