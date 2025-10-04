# MyCC – A Toy Compiler in C (Lex & Yacc)

[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](LICENSE) 

## Table of Contents

- [About](#overview)  
- [Architecture / Tech Stack](#architecture--tech-stack)  
- [Usage](#usage)  
  - [Prerequisites](#prerequisites)  
  - [Build](#build)  
  - [Compiling](#compile)    
- [Contributing](#contributions)  
- [Roadmap](#roadmap)  
- [License](#license)  
- [Contact](#contact)  

## Overview
**MyCC** is a simple compiler built from scratch in **C** using **Lex (Flex)** for lexical analysis and **Yacc (Bison)** for syntax analysis.  
The project demonstrates the full compiler pipeline — from scanning and parsing, to semantic analysis, and finally code generation.  

The goal is to design and implement a **small C-like language** that supports:
- Arithmetic expressions  
- Variables and assignments  
- Conditional statements (`if/else`)  
- Loops (`while`)  
- Functions  

The compiler translates source code into **C code**, which can then be compiled to a native binary using **GCC**.

---

## Architecture / Tech Stack
- **C (GCC)** – Main implementation language  
- **Lex (Flex)** – Lexical analyzer generator  
- **Yacc (Bison)** – Parser generator  
- **Make** – Build automation  

---

## Usage

### Prerequisites
Make sure you have the following installed:
- GCC (`gcc --version`)
- Flex (`flex --version`)
- Bison (`bison --version`)
- Make (`make --version`)

### Build
```bash
 git clone https://github.com/yourusername/mycc.git
cd mycc
make
```

### Compile
./mycc examples/hello.myc -o out.c
gcc out.c -o hello
./hello

## Contributions 

... 

## Roadmap
 
- Lexical Analysis (Tokenizer)
- Parser / Grammar Rulings
- Abstract Syntax Tree (AST)
- Symbol Table and Semantic Analysis 
- Code Generation (Into C)
- Optimizations (?)

## License 

This project is licensed under the MIT license. 

##  Contacts

...
