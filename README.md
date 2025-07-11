# Plugin Compilation
This repository provides tools for compiling C++ code as native modules for Node.js, focusing on two cellular automata algorithms:

1. **Conway's Game of Life**:  
    Implements the classic cellular automaton devised by John Conway. The algorithm simulates the evolution of a grid of cells based on simple rules, demonstrating how complex patterns can emerge from basic interactions. The C++ implementation showcases performance benefits for computationally intensive simulations.


2. **Lenia**:  
    Implements the Lenia cellular automaton, a continuous generalization of cellular automata that allows for more complex and lifelike behaviors. This algorithm highlights the flexibility and efficiency of C++ for simulating advanced, real-time cellular systems.

**How to build**:
    To compile the plugins, navigate to the desired plugin's directory and run `npm install` or `npm i`.
    This will install the necessary dependencies and build the plugin.
    The compiled binaries will be generated in the `out` directory within the plugin's folder.

**Purpose**:  
The goal of this repository is to provide concrete examples of compiling and using native Node.js modules, while illustrating the advantages of integrating C++ for intensive computational tasks such as cellular automata simulations.
