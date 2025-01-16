# Dereferencing a Null Pointer in C++

This repository demonstrates a common C++ error: dereferencing a null pointer.  The code attempts to write a value to a memory location that is not allocated, causing a runtime crash.

## The Problem

The `bug.cpp` file contains the problematic code. The `main` function declares an integer pointer (`ptr`) and initializes it to `nullptr`.  The next line then tries to dereference this null pointer using the dereference operator (`*`), attempting to write `10` to the invalid memory address.

## The Solution

The `bugSolution.cpp` file shows how to fix the issue. Before dereferencing a pointer, it's crucial to check if it's null or not. Proper error handling or allocation prevents crashes.
