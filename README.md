# Joy-of-Pokemon-Observation

# Pokémon Limb Combinations

## Problem Overview

The **Pokémon Conservation Society** is studying Pokémon species and their habitats around the globe. Each habitat contains a number of Pokémon species, and researchers know how many limbs each species has. The total number of limbs for a habitat is also known, but not the exact combination of species. The problem asks us to determine how many different ways the species' limb counts can sum up to the observed total number of limbs in each habitat.

## Problem Statement

Given several habitats, each with a total number of limbs **t** and several species with known limb counts, we need to determine how many different ways we can combine the species to form the exact total number of limbs.

### Input

1. An integer `h` representing the number of habitats.
2. For each habitat:
   - An integer `t` representing the total number of limbs in the habitat.
   - An integer `s` representing the number of species in the habitat.
   - A list of `s` integers representing the number of limbs for each species.

### Output


![image](https://github.com/user-attachments/assets/8b7868fc-d454-481b-a1dc-7cc9e5b63d1b)


For each habitat, output the number of ways to form the total number of limbs using the available species.

Here's the `README.md` file based on the provided instructions:

```markdown
# Pokemon Program - C++ Implementation

## Introduction

This repository contains a C++ program that solves a specific problem. You can either run it locally on your machine using Visual Studio Code or execute it using an online compiler.

## Setup

### Prerequisites

Before running the code locally, make sure you have the following:

1. **MSYS2** or any compatible environment with **GCC** installed (Alternatively, you can use any C++ compiler of your choice).

### Clone the Repository

1. Clone the repository using the command:

   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

## Compilation and Execution

### 1. Save the C++ Code

Save the C++ code in a file named `pokemon.cpp`.

### 2. Compilation

To compile the code, open a terminal and navigate to the directory containing the `pokemon.cpp` file. Then, run the following command:

```bash
g++ -o pokemon pokemon.cpp
```

This will create an executable file named `pokemon`.

### 3. Execution

To run the program, use the following command in the terminal:

```bash
./pokemon
```

### Input Format

For the program to work correctly, provide the input in the following format:

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

### Notes

- For large data sets like:

  ```
  4 1000000000 3 1 1 1 0 3 2 4 5 17 2 2 4 34 3 5 3 2
  ```

  The program may not produce an output on some online compilers (e.g., GDB).

- The program takes approximately **1 second** to compile, and for larger data, it may take **2 to 3 seconds** in Visual Studio Code.

### Alternative Method: Online Compiler

If you prefer not to set up the environment locally, you can simply run the program on an online compiler such as [GDB Online Compiler](https://www.jdoodle.com/c-online-compiler).

## Memory Usage

The program uses **XXX MB** of memory during execution.

## Conclusion


![image](https://github.com/user-attachments/assets/223190a3-b691-4c71-8475-0afcbf93ad2d)


This program is simple to compile and run, and it is optimized for standard input sizes. However, for larger data, running it locally in Visual Studio Code or another IDE is recommended for faster execution.

```
