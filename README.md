<h1 align="center">Generating Assembly Language Instructions from<br> Labelled ICG Tree</h1> 

## Description
This repository contains code for generating assembly language instructions from a labelled Intermediate Code Generation (ICG) tree. It involves translating the ICG tree into assembly language instructions while preserving semantics and optimizing the resulting code for the target machine.

## Usage
To generate assembly code from a labeled ICG tree, follow these steps:

1. Clone the repository to your local machine.
2. Open the project in your `Visual Studio Code` platform.
3. Review and understand the implemented algorithms and methodologies for generating assembly code from the labeled ICG tree.
4. Compile and run the program.
5. Provide the `labeled ICG tree as input` to the program.
The methods are implemented in `JavaScript`.
6. Use the provided `HTML and CSS` code for the user interface, allowing users to input the root node and visualize the inorder display and assembly code.
The program will traverse the tree, generate the corresponding assembly instructions, and display the resulting assembly code.

## Algorithm/Methodology
```
Define a `bin_tree` struct that stores data, label, and pointers to left and right nodes.
Define a `dag` class with methods for initializing the stack, inserting nodes, finding node labels, printing the tree in inorder, swapping registers, popping registers, pushing labels, determining the opcode for arithmetic operations, and generating assembly code.
Implement the above methods in JavaScript.
Initialize a `dag` object and use its methods to insert nodes into the tree, find node labels, print the tree, and generate assembly code for arithmetic expressions.
Compile and run the program.
``` 
<br>
Please note that the provided code is a mixture of HTML, CSS, and JavaScript and requires a web browser to run.
