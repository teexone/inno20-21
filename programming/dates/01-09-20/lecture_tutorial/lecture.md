# Introduction to Programming Software Systems

## Definitions
**Syntax** - a set of rules to regulate the structure of programs and their parts
**Semantics** - the meaning of the constructs  

Syntax << Semantics

 _**Example:**_  

`int x = a + b`  

Syntax:
- `int` is a spec type
- `x` is a name
- `= and +` are operators
- `a + b` is expression


Semantics:
- Allocate memory
- Calculate the expression
- Perform type conversion
- Store the value of the expression
- Make `x` available in the current context

## Memory
Kinds of memory:
- Program - cannot be modified
- Dynamic memory ("Heap") - defined by dynamic semantics
- Stack - defined by static program structure

## Program Execution Layers
- High Level Language
- Assembly Language Program
- Machine Language Program
- Machine Interpretation
- Architecture Implementation

# C Language:
Authors: **Brian Kernighan** and **Dennis Ritchie**
- Syntactically, a C program consists of a sequence of **declarations**.
- Each declaration introduces an entity:
  - Variable
  - Array
  - Type
  - Function

_Note: 0 before a number means that number is in **octal system**_
