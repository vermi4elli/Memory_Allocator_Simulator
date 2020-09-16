# Memory_Allocator_Simulator
## Description
### Brief description
A test of implementing the basic work mechanic of memory allocators (not actually implementing the allocator).  
The algorithm suggests we have a continuous part of memory. There, we can allocate different **blocks**.   
Each block has a **header** and the **data**. **Header** always has a fixed size of 8 bytes.   
That means, to allocate ***10 bytes*** of memory, we need at least ***18 bytes*** of free memory.
The structure of **header**:   
> **[ [current block size : 2 bytes] [previous block size : 2 bytes] [data is occupied : 1 byte] [placeholder : 3 bytes] ]**
### Algorithm description   

## How to use
To use the algorithm, open the file in any IDE with C++ support or use the [C++ shell website to compile the code](http://cpp.sh/).   
Describe your use cases in `main()` function or implement it in separate function, then calling it in `main()` function.
