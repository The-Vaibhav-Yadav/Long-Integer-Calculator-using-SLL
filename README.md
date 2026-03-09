# Long Integer Calculator using Singly Linked List

This project provides a Python implementation that uses a Singly Linked List data structure to construct long integers string digit by string digit. It bypasses conventional variable storage limits by mapping individual digits directly into node values of a custom linked list object, allowing arbitrarily large input.

## Features & Implementation
- **Node Class**: A foundational building block representing a single digit with a pointer to the next structure.
- **LinkedList Class**: Contains methods spanning `append` for populating the number, `pop_first`, basic indexing and traversal logic, and `print_list`.
- **String Parsing**: Reads `int1` and `int2` from user input via stdin routing each discrete character sequentially as a linked list node.

*Note: While arithmetic stubs are indicated within the implementation (such as an `.addition` method invocation), it's highly focused on memory modelling large integer data shapes in raw Python structures.*

### How to use
Run via standard Python environment:
```bash
python3 lab1.py
```
