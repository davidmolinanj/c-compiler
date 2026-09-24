# C-Subset to MIPS Compiler

A custom compiler for a subset of the C programming language, built using **Lex/Flex** and **Yacc/Bison**. It performs lexical, syntactic, and semantic analysis, and generates intermediate MIPS assembly code.

## Features
* **Lexical & Syntactic Analysis:** Tokenization and grammar validation of C-like control flow and data types.
* **Semantic Validation:** Symbol table management (distinguishing variables and constants) and scope checking.
* **Control Structures:** Native support for `if-else` branches and `while` loops.
* **Code Generation:** Generates MIPS assembly instructions (`add`, `sub`, `mul`, `div`, `sw`, `lw`, `beqz`, `b`).

## Requirements
To build and run this project, you need the following tools installed on your system:
* GCC
* Flex
* Bison
* Make

## Build and Execution

1. Compile the project using the provided Makefile:
   ```bash
   make
