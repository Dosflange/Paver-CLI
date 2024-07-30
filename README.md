# Paver-CLI

These is a cleaned-up WIP including the native Paver assembler source I was using for the various implementations of that CPU, notably the [FPGA version](https://github.com/Dosflange/Paver).

Hen.c does not directly implement an assembler. It instead loads the native binary version (!) of the assembler and runs it by emulating a Paver core in order to assemble a new version of itself (the egg).
